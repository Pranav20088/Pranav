CODE FOR SIMPLE INTREST
P=int(input("Pls enter P value:"))
R=int(input("Pls enter R value:"))
T=int(input("Pls enter T value:"))
result=P*R*T/100
print(result)  

CODE FOR FARENHEIT TO CELCIUS
F=int(input("Pls enter Farenheite:"))
Result=5/9*(F-32)
print(Result)

CODE FOR REMAINDER 2
NUM=int(input("Pls enter a number:"))
result=NUM%2
print(result)

CODE FOR AVG. MARKS IN 5 SUBJECTS
e=int(input("Enter the marks scored in English:"))
cs=int(input("Enter the marks scored in Computer Science:"))
m=int(input("Enter the marks scored in Maths:"))
c=int(input("Enter the marks scored in Chemistry:"))
p=int(input("Enter the marks scored in Physisc:"))
AVG=(e+cs+m+c+p)/5
print(AVG)
if AVG < 25:
    print("Student failed")
else:
   print("student passed")

CODE FOR AREA OF n NO.OF CIRCLES
noOfcircle=int(input("Please enter the number of Circles:"))
start=1
radiusofcircle=[]
while start<=noOfcircle:
    radius=int(input("Please enter the radius of the circle:"))
    radiusofcircle.append (radius)
    pi=22/7
    area=pi*radius**2
    print("Area of the circle is",start,"is:",area)
    start +=1
start=1
for x in radiusofcircle:
    print("Radius of circle",start,"is",x)
    start +=1
