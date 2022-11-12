## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: We call it as general purpose because most of they syntex are as if you are speaking like for printing have print() function. It is high level language because it is not written in binary notation i.e (0`s and 1`s) or we can say it is not written directly in machine level language.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q2. Why is Python called a dynamically typed language?
Ans: Python is dynamically typed language because you don`t need to provide data type to any variable it will take automatically.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q3. List some pros and cons of Python programming language?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q4. In what all domains can we use Python?
Ans: Web Techonologies, Data Engineering, Data Science, Machine learning,etc.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q5. What are variable and how can we declare them?
Ans: Variable are nothing but a name given to memory location where value is stored so it can be used in the program. eg name="Nevil".

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q6. How can we take an input from the user in Python?
Ans: Using Input Function (i.e name=input("Please Provide Your Name"))

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans: String

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q8. What is type casting?
Ans: Type  Casting is not but converting one data type to another. For example we can change var="12" to int the var_int=int(var). 
There are are two type of casting:
1.Implicit(python autmatically take care of this casting. example adding int and float value will automatically cast ans in float ) 
2.Explicit(We need to do it in program like example given above)

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans.Yes we can take. 
Example. 
firstName,lastName=input("provide firstname and lastname seperated but space").split()
Print("First Name is: ",firstName)
Print("Last Name is: ",lastName)

>>provide firstname and lastname seperated but space: Nevil Sanghani
>>First Name is: Nevil
  Last Name is Sanghani

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q10. What are keywords?
Ans: Reserved Words that can be used as variable are know as key words like: for, if, else,etc.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans: No we cant use it. This are reserved key words and they have perticular logic/meaning in programming. So if we use it as variable the program will get confused how to use that.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q12. What is indentation? What's the use of indentaion in Python?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q13. How can we throw some output in Python?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q14. What are operators in Python?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q15. What is difference between / and // operators?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

------------------------------------------------------------------------------------------------------------------------------------------------------------------
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans:
num=int(input())
if num%2==0:
    print("even")
else:
    print("odd")

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q18. What are boolean operator?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Ans:

1 or 0 : 1

0 and 0 : 0

True and False and True : False

1 or 0 or 0 : 1
------------------------------------------------------------------------------------------------------------------------------------------------------------------
Q20. What are conditional statements in Python?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q21. What is use of 'if', 'elif' and 'else' keywords?

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans:

age=int(input())
if age>=18:
    print("I can vote")
else:
    print("I can't vote")
	

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
sum_even=0
for i in numbers:
	if i%2==0:
		sum=sum+i

Print(sum)

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans:

l=[int(a) for a in input().split()]
if len(l)!=3:
    raise Exception("Please provide only 3 inputs")
else:
    l.sort()
    print("Greatest Number is: ",l[len(l)-1])
------------------------------------------------------------------------------------------------------------------------------------------------------------------
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans:

numbers = [12, 75, 150, 180, 145, 525, 50]
result_list=[]
for i in numbers:
    if i>500:
        break
    elif i>150:
        continue
    elif i%5==0:
        result_list.append(i)
print(result_list)   
