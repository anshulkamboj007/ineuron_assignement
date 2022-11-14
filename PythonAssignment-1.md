## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
ans:- python is not special for any specific purpose,
      highlevel as it is independent of computer used

Q2. Why is Python called a dynamically typed language?
ans:- values assigned at time of runtime

Q3. List some pros and cons of Python programming language?
ans:- cons:- high memory consumption,slow
       pros:- flexible,many libraris

Q4. In what all domains can we use Python?
ans:- maths,dataprocessing, image processing

Q5. What are variable and how can we declare them?
ans- variable hold values which can be predeclared, or generated during process,
     can be declared by simple  variablename = value 

Q6. How can we take an input from the user in Python?
ANS- using input()

Q7. What is the default datatype of the value that has been taken as an input using input() function?
ANS- STRING

Q8. What is type casting?
ans:- conversion of one data type to another

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ans:- yes ,  declare required variables  
       a,b= input("enter 2 numbers ").split()

Q10. What are keywords?
ans:- reserved words

Q11. Can we use keywords as a variable? Support your answer with reason.
ans:- no,they are reserved by python for predefined task

Q12. What is indentation? What's the use of indentaion in Python?
ans:- space at beginning of line is indentation . use in python to indicate a block of code

Q13. How can we throw some output in Python?
ans:-using print

Q14. What are operators in Python?
ans:- special symbols to indicate computation

Q15. What is difference between / and // operators?
ans:- / div, // mod div

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ans:- 
c="iNeuron"
print(c*4) 

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ans:-
a=int(input("enter 1 numbers:"))
if a%2==0:
    print("num is even")
else:
    print("num is odd")

Q18. What are boolean operator?
ans:- and, or, True,False,not

Q19. What will the output of the following?
```
1 or 0
ans:-1

0 and 0
ans:-0

True and False and True
ans:-False

1 or 0 or 0
ans:-1
```

Q20. What are conditional statements in Python?
ans:- check for conditions if, while,else ,elif

Q21. What is use of 'if', 'elif' and 'else' keywords?
ans:- if:- do operation if condition 1 is true
      elif:-do operation if condition 2 is true
      else:- do operation if none condition is true

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ans:-
age=int(input('enter age'))

if age >= 18 :
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ans:-
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in numbers :
    print("num:",i)
    if i%2==0:
        sum=sum+i
    print ("sum is: ",sum)
    


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ans:-
a,b,c=input(" enter 3 numbers").split()

num=[int(a),int(b),int(c)]
d=0

for i in num:
    if d<i:
        d=i

print(" max num:",d)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ans:-

numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i%5==0:
        if i<150:
            if i<500:
                print (i)