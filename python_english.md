# Python for kids in local languages

## Why?

Normally, programming books are written in English language. This makes programming accessible only to those who know English. 
This attempt is to create a resource in different local languages so that kids can learn programming in their mother tongue. 
By thinking and programming in our mother tongue we can do a much better job. It becomes more natural.

## Introduction
Many people think programming is a very tough thing. Most people have a fear of computers. 
They think only a few people can program. Let me clarify it for you. Anyone can program. If you can think and if you can communicate, you can program.
Programming is nothing but talking to a computer. If I have to speak to you, I speak in Telugu. If I have to speak to an American, I speak in English. If I have to speak to a computer, I speak in a programming language. That’s it.

Just like there are many natural languages, there are many programming languages. Python is one such programming language. This is a very easy language to learn and it comes pre installed in many computers so you don’t need to do anything else. I will be using Ubuntu Linux to show the examples. Python comes pre installed in Ubuntu. If you have a Windows machine ask your parents to find instructions and install Python before you start reading the next chapters.

### So what is programming? Why do we need to learn programming?

The computer is a very powerful multi purpose machine which can be used to do a lot of things. But it cannot do the things on its own. It needs to be told what to do. And we use programming languages to tell it what to do. So basically a program is a sequence of instructions which tells a computer what to do. And just like we only understand when someone tells us in a language we know, computers do the actions only when they are told in a language they know.

Let us now look at programming through a simple example.

Let’s say I give you 5 cards. Each card has one number on it. Let’s say the numbers are 5,1,3,8,4. Find the largest number in the 5 cards. 

What is it? 

We all know it’s 8. 

But how did you find it? In your mind you very quickly did some calculations. You compared the numbers and came up with a solution.

Now let’s make this interesting. I give you a puppet/robot (Or you can try this experiment with your friend). It will only do the actions that you tell it to do. It can understand your language. The job for you is this. Can you tell it step by step what actions it should do to find the largest number in the cards? 

Take your time. Think. I will tell what I would tell the robot below, but you have to think first. 

Try this out with your friend. Tell them instructions and lets see is at the end of following your instructions your friend is left with the largest number in their hand.
.

.

.

.

.

.

.

.

.

.

I would tell the following:

1. Pick the first card.
2. Pick the next card.
3. If the new card is bigger then keep that in your hand and drop the older card. Basically keep the card with the larger number and drop the card with the smaller number.
4. Do steps 2 and 3 until you run out of cards.
5. The card in your hand is the largest card.

You have just written your first program. In fact, this sequence of steps is called an algorithm.

But since computers can’t understand English, we have to rewrite the above program in a language they understand like Python. And this is what you will be learning.

Good. You have understood the basics of programming. Time to take a rest. Come back tomorrow and you can start interacting with your computer using Python.

--------------------------------------------------------------------------------------------------------------------

## First steps

Welcome back. Today we will start with Python coding. Open the terminal/command prompt on your computer(ask your parents if you don't know how) and type python.

`>python`

You will get something like below. You are now in the python interpretor.

```
Python 2.7.12 (default, Dec  4 2017, 14:50:18) 
[GCC 5.4.0 20160609] on linux2
Type "help", "copyright", "credits" or "license" for more information.

>>> 
```
You can start communicating with your computer by typing commands after ">>>"

As I explained earlier, you can tell the computer what to do in it's language. So, the first thing we will ask the computer to do is ask it to print something. And how you do that, we do that by using the print() function. So, what is print(). print() is like telling the computer,"Hey computer, take whatever I put in between ( and ) and display it". Instead of typing the full English sentence everytime and since the computer does not know English, we use print() in python language. Let's try it out.

`>>>print(4)`

What did it output? It would have displayed 4. Let's try more.

`>>>print(987)`

`>>>print(54)`

Now,let's try something else.

`>>>print("Hello World")`

Did you see. I used " and ". This is another rule in the python language. When you use numbers 4, 987, 54 etc we don't need to use "". But if we are working with words and sentences then we need to use " ". When we use " ", they are called as strings.

Ok. Good. This is all great. But the computer is not doing anything useful. It is just displaying what we give it. Let's try something more useful.

`>>>print(4+5)`

9

Wow! The computer did the addition and gave the answer for you. What about

`>>>print(45675456+98373747)`

144049203

Cool. Can python also do other mathematical operations? Let's try it out. You can use the following in the python language:

* Multiplication - *
* Division - /
* Addition - +
* Subtraction - -
* Modulo - % (Modulo operator gives the reminder after division)

Try playing around with these operators at the prompt. Don't worry, you will not break the computer. Type whatever you want and see what the computer displays.

Right now you have learnt to ask the computer to do math problems for you. Go ahead and use the python language to do your math homework :)

Let's try to make the computer do a math homework problem.

Problem: Raja has 5 apples. Rani has 4 apples. How many apples do both of them have together.

How do you generally solve this? You will do something like this on paper.

Number of apples Raja has=5

Number of apples Rani has=4

Total number of apples=Number of apples Raja has + Number of apples Rani has=5+4=9

Now let's see how you would do this in python.

```python
>>>Number_of_apples_raja_has=5
>>>Number_of_apples_rani_has=4
>>>Total_apples=Number_of_apples_raja_has+Number_of_apples_rani_has
>>>print(Total_apples)
```

See, so simple. It's like you wrote on paper. Only thing is there are some rules for python. If you see, "Number of apples rani has" became "Number_of_apples_rani_has". For now think that it's because python does not ike spaces too much. So we replaced the space with '\_'. Or you could have used "Numberofapplesranihas". Anything is fine as long as space is not there.

Number_of_apples_rani_has is called as a variable in python. So what did you do above. You told the computer to store apples raja has in Number_of_apples_raja_has variable and apples rani has in Number_of_apples_rani_has variable. Then you told the computer to add those two variables. Finally you asked the computer to print the answer. It's as simple as that. Tell the computer one step at a time, in a language it can understand and it will do the tasks and give you the result.

-------------------------------------------------------------------------------------------------------------

## What's life without conditions?

So you have learnt to tell the computer, Number_of_apples_raja_has=5 and also learnt to ask it to do some math problems for you. BTW, Number_of_apples_raja_has=5 is called as assignment. You are assigning the value 5 to the variable Number_of_apples_raja_has. We can think of assignment as one kind of sentence in the Python language.

Let's change the above problem statement slightly.

Problem: Raja has 5 apples. Rani has 4 apples. Who has more apples?

Can you write a Python program to solve this?

You will start by saying

`>>>Number_of_apples_raja_has=5`

`>>>Number_of_apples_rani_has=4`

But after this what? If you don't know some words in a langauge you cannot explain an idea. Similarly, since you don't know how to tell a computer to check for a condition you are stuck.

You can't obviously say:

`>>>If Number_of_apples_raja_has is more than Number_of_apples_rani_has then Raja is the winner. Otherwise Rani is the winner.`

You can't say the above because the computer does not know English and it cannot understand the above sentence. So lets see how we can create a similar sentence in Python. In Python such sentences are represented by "if else" statements.

You have to follow some rules to write such sentences. The condition sentence is written in Python as follows.

```python

if condition:
    statements    
else:
    statements
    
```

So the sentence is constructed as follows. You start with 'if' then write the condition then end with ':' to say to the computer that the condition is over. Then hit 'enter' key on your keyboard. Next is very important in Python language. You have to indent the next line. That is, hit 'space' 4 times or hit 'tab' once. Then you can write assignment statements which you learnt earlier. You can write as many as you want.

After you are done with 'if', you can move to 'else'. If you don't have an else condition you can stop here. Else sentence is easier. You just type 'else'(note the indentation), then ':' hit 'enter', hit 'tab' and type your statements.

Lets now look at the conditions supported in Python. They are

* Equals: a == b. (That is, in English we say a is equal to b. In Python it's a == b)

* Not Equals: a != b

* Less than: a < b

* Less than or equal to: a <= b

* More than: a > b

* More than or equal to: a >= b

A little hard no? It's ok. Once you practice a few it will become easy.

Now let's see with this new knowledge how can we write the sentence 'If Number_of_apples_raja_has is more than Number_of_apples_rani_has then Raja is the winner. Otherwise Rani is the winner.' in Python

```python
Number_of_apples_raja_has=5`
Number_of_apples_rani_has=4`

if Number_of_apples_raja_has > Number_of_apples_rani_has:    
    print("Raja is the winner")    
else:
    print("Rani is the winner")

```

See how cleanly and easily we are able to convert an English sentence into Python. 
'If' became 'if'

'is more than' became '>'

'then' became ':'

'Otherwise' became 'else'

That's all. This is why Python is such an easy language to learn.

This is how you write all programs. Understand the problem in your language(English/Telugu). Think of a solution in your langauge. Convert the sentences into Python language. Feed it to computer and let the computer solve the problem for you.

Let's try this out with another small example.

Problem: Take a number. Check if it is even or odd.

Solution in English: Let number be stored in variable 'num'. If the remainder when num is divided by 2 is zero then it's an even number. Otherwise it's an odd number. So we need to take the number. Calculate it's remainder and then check the condition on the remainder.

Solution in Python:

```python

num=5
remainder=num%5
if remainder==0:
    print("Even number")
else:
    print("Odd number")

```
We stored the remainder value in a new variable called 'remainder' and then used that in the condition.

Before we finish with conditions, let's look at couple of final concepts. 

Let's go back to the Raja, Rani, apples problem. We saw how we can represent "If Number_of_apples_raja_has is more than Number_of_apples_rani_has then Raja is the winner. Otherwise Rani is the winner." in Python. But what if I add another condition. "If Number_of_apples_raja_has is more than Number_of_apples_rani_has then Raja is the winner. Otherwise Rani is the winner. If both have equal number of apples, then it's a tie".

You could do something like

```python
if Number_of_apples_raja_has > Number_of_apples_rani_has:    
    print("Raja is the winner")    
if Number_of_apples_rani_has > Number_of_apples_raja_has: 
    print("Rani is the winner")
if Number_of_apples_rani_has == Number_of_apples_raja_has: 
    print("It's a tie")
```
But Python has a more elegant language construct, 'elif'.

Just like 'else', 'elif' is also optional. You can also have any number of 'elif's. Python will look at all the elif conditions and find the the first TRUE one and execute those statements.

The syntax(language rules) of elif is

```python
if condition1:
   statement(s)
elif condition2:
   statement(s)
elif condition3:
   condition(s)
else:
   statement(s)
```

Now that we new a word in Python language lets use it to write the solution to the above problem. We can write "If Number_of_apples_raja_has is more than Number_of_apples_rani_has then Raja is the winner. Otherwise Rani is the winner. If both have equal number of apples, then it's a tie" in Python as

```python
if Number_of_apples_raja_has > Number_of_apples_rani_has:    
    print("Raja is the winner")    
elif Number_of_apples_rani_has > Number_of_apples_raja_has: 
    print("Rani is the winner")
else: 
    print("It's a tie")
```

Also, just like any other language you can write different sentences with the same meaning. For example a different solution to the above problem but using '<'(less than) can also be written. Why don't you try it out. Some other excercises you should try out before moving on:

1. Store marks from different subjects. Find their total. If total is above or equal to 80, give A grade. Else, give B grade.
2. Check if an year is a leap year or not.
3. Create your own problems and solve them :)

For the final concept in conditions, lets look at logical operators.

Problem: Find if a number is divisible by 5 and 11.

```python
num=55
if(num%5==0):
    print("Divisble by 5")
if(num%55==0):
    print("Divisble by 11")
```

What will the above program do? It will output:

Divisible by 5
Divisible by 11

But we want to print:

Divisible by 5 and 11

So how can we do it. To combine two conditions, we use logical operators. The most common logical operators in Python are 'and' and 'or'. When you use 'and' only when the both the conditions are true the overall condition becomes TRUE. When you use 'or' even if one of the conditions is true the overall condition becomes TRUE. So using the logical 'and' operator we can write the solution for the above problem as
(I am not showin the prompt >>> from now on)

```python
num=55
if(num%5 == 0 and num%11 == 0):
    print('Divisible by 5 and 11')
else:
    print('Not Divisible by 5 and 11')
```
Great. Now lets try to combine all the concepts into one problem. See if you can solve it.

Problem: Store marks of different subjects. Find their total. If the total is above or equal to 80 give A grade. If total is between 60 and 80 give B grade. If total is between 40 and 60 give C grade. If total is below 40 give F grade.


## Lists and Loops

Let's go back to the first problem. Can we solve it with the Python we have learnt so far?

Problem: Let’s say I give you 5 cards. Each card has one number on it. Let’s say the numbers are 5,1,3,8,4. Find the largest number in the 5 cards.

I think we can do it like this

```python
number1=5
number2=1
number3=3
number4=8
number5=4
largest=number1
if number2 > largest:
    largest=number2

if number3 > largest:
    largest=number3

if number4 > largest:
    largest=number4

if number5 > largest:
    largest=number5

print(largest)
```

Great. This works. But what if the problem was to find the largest in 100 numbers. Or 1000 numbers. Or 10,000 numbers. Can you imagine how long the program will be and how long it will take to type it. We are missing something. We are missing the vocabulary to store things as a group. We are missing the vocabulary to repeat things. If you look back, our English language solution to the problem was:


1. Pick the first card.
2. Pick the next card.
3. If the new card is bigger then keep that in your hand and drop the older card. Basically keep the card with the larger number and drop the card with the smaller number.
4. Do steps 2 and 3 until you run out of cards.
5. The card in your hand is the largest card.

Step 4 is the important one. Look how we just said, do.... until. Lets see how we can do the same in Python.

First, lets look at how to group things. Python gives us lists. So instead of storing the invidual numbers in individual variables like number1, number2, number3 etc, we can store all the numbers in one list. We can define a list using \[\].

```python
numbers=[5,1,3,8,4]
```

Done. So much easier than defining one variable for each number. But how can we access the individual numbers? Easy, you can access them as numbers\[0\], numbers\[1\], numbers\[2\], numbers\[3\], numbers\[4\].

Did you notice something quirky? The first numbers was accessed as numbers\[0\]. The second was accessed as numbers\[1\] and so on. That means list element counting starts from 0. I know, I know. All your life you have counted things starting with 1. But in programming, for historical and other reasons, for list elements, the counting starts from 0. So if you want the 100th element in the list you can access it as numbers\[99\] if the list name is numbers.

Second, we just need the vocabulary to execute some statements repeatedly. And for that in Python, we have the 'for' statement.

The syntax of the 'for' statement is
```python
for variable in list:
    statements
```
In the above, 'variable' is the name of the variable which will take one value from the 'list' at a time. 'statements' are executed as many times as the number of 'list' elements are there. So, if the list has 5 elements, then the statements will be executed 5 times. Lets look at the simplest example.

```python
avengers=["iron man","spiderman","hulk","captain america","thor"]

for x in avengers:
    print(x)
```
The above program will print the name of the avengers one at a time.

With these two new concepts lets see how we can solve the largest number problem. The pseudo code can be

1. Store numbers in a list
2. Initialize largest to first element
3. for number in list
4. if number is greater than largest
5. Assign number to largest
5. Print largest.

Now lets do the actual Python code with the correct syntax.

```python
numbers=[5,1,3,8,4]
largest=numbers[0]
for number in numbers:
    if number > largest:
        largest=number
    

print(largest)
```

Notice how close the Python program is to our general language. You just need to be careful with the indentation and the syntax.

Let's do a quick revision. In Python language we have learnt:
1. Assignment
2. Conditionals
3. Loops

With these three constructs you can write almost any program you want. Programming is really so simple. Just these 3 statements and you can make the computer do whatever you want.

Let's see if you can solve the following problem by yourself.

Problem: Take 10 numbers in a list. Take a number you have to search in another variable. Search for the second number in the list. If the number is found, print found. If not, print not found.

Discuss with your parents or friends. Take your time. Work slowly one step at a time. This is one of the most common problem in computer science. So if you get this you have done a great job. Once you are done, let's go to the next chapter.
