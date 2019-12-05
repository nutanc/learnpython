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

\>python

You will get something like below. You are now in the python interpretor.

Python 2.7.12 (default, Dec  4 2017, 14:50:18) 
[GCC 5.4.0 20160609] on linux2
Type "help", "copyright", "credits" or "license" for more information.

\>\>\> 

You can start communicating with your computer by typing commands after ">>>"

As I explained earlier, you can tell the computer what to do in it's language. So, the first thing we will ask the computer to do is ask it to print something. And how you do that, we do that by using the print() function. So, what is print(). print() is like telling the computer,"Hey computer, take whatever I put in between ( and ) and display it". Instead of typing the full English sentence everytime and since the computer does not know English, we use print() in python language. Let's try it out.

\>\>\>print(4)

What did it output? It would have displayed 4. Let's try more.

\>\>\>print(987)

\>\>\>print(54)

Now,let's try something else.

\>\>\>print("Hello World")

Did you see. I used " and ". This is another rule in the python language. When you use numbers 4, 987, 54 etc we don't need to use "". But if we are working with words and sentences then we need to use " ". When we use " ", they are called as strings.

Ok. Good. This is all great. But the computer is not doing anything useful. It is just displaying what we give it. Let's try something more useful.

\>\>\>print(4+5)

9

Wow! The computer did the addition and gave the answer for you. What about

\>\>\>print(45675456+98373747)

144049203

Cool. Can python also do other mathematical operations? Let's try it out. You can use the following in the python language:

* Multiplication - *
* Division - /
* Addition - +
* Subtraction - -

Try playing around with these operators at the prompt. Don't worry, you will not break the computer. Type whatever you want and see what the computer displays.

Right now you have learnt to ask the computer to do math problems for you. Go ahead and use the python language to do your math homework :)

Let's try to make the computer do a math homework problem.

Problem: Raja has 5 apples. Rani has 4 apples. How many apples do both of them have together.

How do you generally solve this? You will do something like this on paper.

Number of apples Raja has=5

Number of apples Rani has=4

Total number of apples=Number of apples Raja has + Number of apples Rani has=5+4=9

Now let's see how you would do this in python.

\>\>\>Number_of_apples_raja_has=5

\>\>\>Number_of_apples_rani_has=4

\>\>\>Total_apples=Number_of_apples_raja_has+Number_of_apples_rani_has

\>\>\>print(Total_apples)

See, so simple. It's like you wrote on paper. Only thing is there are some rules for python. If you see, "Number of apples rani has" became "Number_of_apples_rani_has". For now think that it's because python does not ike spaces too much. So we replaced the space with '\_'. Or you could have used "Numberofapplesranihas". Anything is fine as long as space is not there.

Number_of_apples_rani_has is called as a variable in python. So what did you do above. You told the computer to store apples raja has in Number_of_apples_raja_has variable and apples rani has in Number_of_apples_rani_has variable. Then you told the computer to add those two variables. Finally you asked the computer to print the answer. It's as simple as that. Tell the computer one step at a time, in a language it can understand and it will do the tasks and give you the result.
