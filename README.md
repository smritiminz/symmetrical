# symmetrical
maths=int(input("Enter the markes of maths: "))
phy=int(input("Enter the markes of phy: "))
bio=int(input("Enter the markes of bio: "))
chem=int(input("Enter the markes of chem: "))
eng=int(input("Enter the markes of eng: "))
total=maths+phy+bio+chem+eng
avg=total/5
if avg>=80 and avg<=100:
    print("grade: A")
elif avg>70 and avg<=89:
    print("grade: B")
elif avg>=60 and avg<=69:
    print("grade: C")
elif avg>=50 and avg<=59:
    print("grade: D")
elif avg>=0 and avg<=49:
    print("Fail")
else:
    print("Invalid Input")
