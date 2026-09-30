student= int(input("How many students: "))
print()

for i in range(student):
    print("Student", i + 1)
 
ename = input("Enter name: ")
print()
ACT1 = int(input("Activity 1: "))
ACT2 = int(input("Activity 2: "))
ACT3 = int(input("Activity 3: "))
sum = ACT1 + ACT2 + ACT3
average =sum/ 3

print("Average:",average)

if average >=90:
    print("Status:EXCELLENT")
elif average >=80:
    print("Status:VERY GOOD")
elif average >=75:
     print("Status:PASSED")
else:
     print("Status:FAILED")
