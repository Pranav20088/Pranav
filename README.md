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

CODE FOR THE VOLUME OF 3D SHAPES
print("If you want Volume of Sphere : Press 1")
print("If you want Volume of Cone : Press 2")
print("If you want Volume of Cube : Press 3")
print("If you want Volume of Cuboid : Press 4")
print("If you want Volume of Hemisphere : Press 5")
print("If you want Volume of Cylinder : Press 6")
pi=22/7
x=int(input("Please select the option:"))
if x==1:
    pi=22/7
    r=int(input("Please enter the radius:"))
    Volume=4/3*pi*r**3
    print("The volume of Sphere is",Volume)
elif x==2:
    r=int(input("Please enter the radius:"))
    h=int(input("Please enter the height:"))
    Volume=1/3*pi*h*r**2
    print("The volume of Cone is",Volume)
elif x==3:
    l=int(input("Please enter the length of the side:"))
    Volume=l**3
    print("The volume of Cube is",Volume)
elif x==4:
    l=int(input("Please enter the length of the side:"))
    b=int(input("Please enter the breadth of the side:"))
    h=int(input("Please enter the height of the side:"))
    Volume=l*b*h
    print("The volume of Cuboid",Volume)
elif x==5:
    r=int(input("Please enter the radius:"))
    Volume=2/3*pi*r**3
    print("The volume of Hemisphere is",Volume)
elif x==6:    
    r=int(input("Please enter the radius:"))
    h=int(input("Please enter the height:"))
    Volume=pi*h*r**2
    print("The volume of Cylinder is",Volume)
else:
    print("You have not choosen the correct option please choose the correct option and try again")
