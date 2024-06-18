# conditional-statements-in-python
"Write a python script to enter student number, name, marks in c, c++ and java calculate and display total marks, average, result and grade. Print fail if student average is less than 70.  "
number=int(input("enter your number:"))
name=input("enter your name:")
a,b,c=map(int,input("enter your marks in c,c++,java:").split())
average=(a+b+c)/3
result=a+b+c
print("Average:",average)
print("total marks:",result)
print("Result:",result)
if(average<100 and average>70):
    print("Pass")
    if(average<100 and average>=90):
          print("Grade: A ")
    elif(average<90 and average>=80):
          print("Grade: B ")
    elif(average<80 and average>=70):
          print("Grade: C ")
  
else:
    print("Grade: D ")
    print("Fail")
