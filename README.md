unit=int(input("Enter the unit:"))

if(unit<100):
    total=unit*0
    print("Total Amount: Rs.",total)
elif(unit>100 and unit<=200):
    total=(unit-100)*5
    print("Total Amount: Rs.",total)
elif(unit>200 and unit<=350):
    total=500+(unit-200)*10
    print("Total Amount: Rs.",total)
elif(unit>350 and unit<=450):
    total=2000+(unit-350)*15
    print("Total Amount: Rs.",total)
else:
    total=3500
    print("Total Amount: Rs.",total)
