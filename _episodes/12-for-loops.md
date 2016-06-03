---
layout: episode
title: "For Loops"
teaching: 10
exercises: 10
questions:
- "How can I make a program do many things?"
objectives:
- "Explain what for loops are normally used for."
- "Trace the execution of a simple (unnested) loop and correctly state the values of variables in each iteration."
- "Write for loops that use the Accumulator pattern to aggregate values."
keypoints:
- FIXME
---
FIXME: lesson content.

> ## Iterating through lists
> Suppose we are given a long list of items and we would like to look at its content item by item. We can certainly do this by displaying each item:
objectives
>
> ~~~
> print(objectives[0])
> print(objectives[1])
> print(objectives[2])
> ~~~
> {: .source}
>
> However, if we have a long list we would like to iterate through its elements without writing a print statement for each item.
> Let's consider the list:
>
> ~~~
> listOfNumbers = [1,2,3,4,5,6,7,8,9,10]
> ~~~
> {: .source}
>
> We can display its items using the following for-loop statement:
>
> ~~~
> for item in listOfItems:
>   print(item)
> ~~~
> {:.source}
>
> In this case `listOfItems` is a list of integers. But the one can write a for-loop
> for any list.
>
> Create a for loop which prints the elements of the list `objectives`.
{: .challenge}

> For-loops are very useful also for creating (or modifying) long lists which have a particular structure. Let's create a list of all integers from 1 to 100.
>
> ~~~
>
> for
> ~~~
> {:.source}



> An alternative way of displaying the elements is to use the index of the list.


> ## From 1 to N
> Often we want to iterate from 1 to N when N is a big number. We don't want to create
> the list of those numbers by hand. Python has a useful built-in function called `range`.

> Python has a special built-in function `range` which can easily generate integers. `range` can accept 1-3 parameters. If one parameter is input, range creates an array of that length, starting at zero and incrementing by 1. If 2 parameters are input, range starts at the first and ends just before the second, incrementing by one. If range is passed with 3 parameters, it starts at the first one, ends just before the second one, and increments by the third one.

> Execute the following commands to understand the behavior of the `range` function.
>
> ~~~
> for i in range(3):
>   print(i)
>
> for i in range(2,5):
>   print(i)
>
> for i in range(2,10,3)  
>   print(i)
> ~~~
>
> {:.source}
>
> Write a for loop which:
> 1) creates a list of the squares of the even integers from 1 to 100,
> 2) calculates the sum of the squares of the even integers from 1 to 100.
{: .challenge}

> ## TODO
> * create a list .append()
> * do some summing over a list


> ## Tracing Execution
>
> Create a table showing the numbers of the lines that are executed when this program runs,
> and the values of the variables after each line is executed.
>
> ~~~
> total = 0
> for char in "tin":
>     total = total + 1
> ~~~
> {: .source}
{: .challenge}

> ## Reversing a String
>
> Fill in the blanks in the program below so that it prints "nit"
> (the reverse of the original character string "tin").
>
> ~~~
> original = "tin"
> result = ____
> for char in original:
>     result = ____
> print(result)
> ~~~
> {: .source}
{: .challenge}
