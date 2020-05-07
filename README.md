# Resistor-value-calculator-in-python

Black="Black";x1ohms='x1ohms'
Brown="Brown";x10ohms='x10ohms'
Red="Red";x100ohms='x100ohms'
Orange="Orange";x1Kohms='x1Kohms'
Yellow="Yellow";x10Kohms='x10Kohms'
Green="Green";x100Kohms='x100Kohms'
Blue="Blue";x1Mohms='x1Mohms'
Violet="Violet";x10Mohms='x10Mohms'
Grey="Grey";x100Mohms='x100Mohms'
White="White";x1Gohms='x1Gohms'
Gold="Gold"
Silver="Silver"
a=str(input("Band 1 color="))
b=str(input("Band 2 color="))
c=str(input("Band 3 color="))
d=str(input("Band 4 color="))
if a==Black:
    digit_one=0;print(digit_one)
elif a==Brown:
    digit_one=1;print(digit_one)
elif a==Red:
    digit_one=2;print(digit_one)
elif a==Orange:
    digit_one=3;print(digit_one)
elif a==Yellow:
    digit_one=4;print(digit_one)
elif a==Green:
    digit_one=5;print(digit_one)
elif a==Blue:
    digit_one=6;print(digit_one)
elif a==Violet:
    digit_one=7;print(digit_one)
elif a==Grey:
    digit_one=8;print(digit_one)
elif a==White:
    digit_one=9;print(digit_one)
if b==Black:
    digit_two=0;print(digit_two)
elif b==Brown:
    digit_two=1;print(digit_two)
elif b==Red:
    digit_two=2;print(digit_two)
elif b==Orange:
    digit_two=3;print(digit_two)
elif b==Yellow:
    digit_two=4;print(digit_two)
elif b==Green:
    digit_two=5;print(digit_two)
elif b==Blue:
    digit_two=6;print(digit_two)
elif b==Violet:
    digit_two=7;print(digit_two)
elif b==Grey:
    digit_two=8;print(digit_two)
elif b==White:
     digit_two=9;print(digit_two)
if c==Black:
    digit_three=x1ohms;print(digit_three)
elif c==Brown:
    digit_three=x10ohms;print(digit_three)
elif c==Red:
    digit_three=x100ohms;print(digit_three)
elif c==Orange:
    digit_three=x1Kohms;print(digit_three)
elif c==Yellow:
    digit_three=x10Kohms ;print(digit_three)
elif c==Green:
    digit_three=x100Kohms;print(digit_three)
elif c==Blue:
    digit_three=x1Mohms;print(digit_three)
elif c==Violet:
    digit_three=x10Mohms;print(digit_three)
elif c==Grey:
    digit_three=x100Mohms;print(digit_three)
elif c==White:
    digit_three=x1Gohms;print(digit_three)
if d==Gold:
    Tolerance=5 
    print(Tolerance)
else:
   Tolerance=10 
   print(Tolerance)
print("Resistance_value="+ str(digit_one)+str(digit_two)+str(digit_three)+"Tolerance is +/- "+str(Tolerance)+"%")
