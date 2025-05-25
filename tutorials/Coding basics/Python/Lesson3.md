#Lesson 3 basic programming structures

##Conditional statements :
   These are selections, which helps decide what to do if a condition applies.
    - **"IF":**
        ```python
        if (something true):
            # do something
        else:
            # do something else
        ```
    - **"OR":**
        ```python
        if (something OR something_else) == true:
            # do this 
        else:
            # do something else
        ```    
    - **"AND":**
        ```python
        if (something AND more) == true:
            # do this
            # If only “something” or only “more”, than go to else part.
        else:
            #do anything else
        ```    

[Check Codecademy](https://www.codecademy.com/resources/docs/python/conditionals)  about condition statements, and check the condition statement's python part
[W3 Schools - python if-else](https://www.w3schools.com/python/python_conditions.asp)

5. Iteration (loops):
Loops enable the repetition of certain tasks until a condition is met. This helps in automating repetitive tasks and managing data efficiently.
For example I would like to print numbers from 1 to 10 into the console. I can do this like:
    ```python
    print(“1”)
    print(“2”)
    print(“3”)
    print(“4”)
    print(“5”)
    print(“6”)
    print(“7”)
    print(“8”)
    print(“9”)
    print(“10”)
    ```

but not so efficient, if I would like to print it from 1 to 10 000 right? So need to find a lazy solution:

    ```python
    for i in range(10): # i is for "index" 
        print(i+1)
    ```
<em> says: go through the numbers 10 times start from 1
Try out [in an online editor](https://www.online-python.com/) what happens if you print i and not i+1! 

So what excatly is i??
i is "index". Thanks. What is index? Index is a reference number which tells you the position of an item in a list, array, string,
You have a box of fruits:
Index:   0     1     2     3
Fruits:  🍎   🍌   🍇   🍉
In programming we do not start numbering them from 1 but from 0. So in a list you have four element and thats why the lenght of the list is 4, it has 4 indexes: 0, 1, 2, 3.
And WHHHHHYYY? It comes from the early days of programming, if you really interested and need some reading for accepting this easier here is a [Medium article](https://medium.com/arvatotech/starting-from-zero-the-logic-behind-zero-based-indexing-30703702d874) about the why :)

Lets practice a little!

In coding you will use variables all the time. What is a variable?
Variable is something which is phrased in English (please do not give variable names on your native language, easily became a very very, very bad practice) and has a meaning for you and anyone who reads the code later, and can find out what the hell is going on... And this variable has a value. In mathematic it was X, but a variable can be anything you can imagine, numbers, words or whole sentences (strings in programming), lists, etc.

Now just play a bit with numbers:

1.	Your first task is to create a variable, give them a value: 10. Then in a loop print out numbers from 10-100. 
to do this first step, look through the lesson of [w3schools](https://www.w3schools.com/python/python_for_loops.asp) about loops. There is also a code runner, you can try it out yourself right there.
There is more possible solution, try out as many as you can.

<em> Hint! 

You might need something from this operations:
" > " :  greater than
" >= " : greater or equal
" != " : not equal
" == " : equal

you can add value to a variable in a loop like:
* var = var+2
* var +=2 
* var =+2 

multiple:
* var*2

divide:
* var = var/2
</em>

and you can step out any time your iteration if a condition meets with break.
``` python
    if myvariable > 1000:
        break 
```

Reference for self-study:
- [this codecademy page](https://www.codecademy.com/resources/docs/python/operators)
- [variables](https://www.codecademy.com/resources/docs/python/variables)
- [variables 2](https://www.w3schools.com/python/python_variables.asp)
- [Self-check with python variables exercises](https://www.w3schools.com/python/python_variables_exercises.asp)


2.	Your second exercise:
a.	create a variable with the value of 1000.
b.	divide it with 10 in every loop
c.	until it is bigger than 1

3.	Now get a bit harder. Print every odd number between 30 and 50.
    Hint:
    with var%2 will result the remaining.
    if var = 4:
        print (var%2) will result 0. (4:2 = 2, and there is nothing remains).

    if var=5:
        print(var%2) will result 1 (5:2 = 1, plus 1 remains)

    if var=100:
        print(var%10) will result 0 as (100:10 = 10 and nothing remains.)

    if var=109%10 will result 9 as (109:10=10 and remains 9).

    if and only you are trying hard but not succeed, check [this](https://allinpython.com/print-odd-numbers-from-1-to-100-in-python/) out.

4. Data types in Python
By this time you already know numbers. There is a lot more variable type in python.
    [built in datatypes](https://www.w3schools.com/python/python_datatypes.asp)
    [numbers](https://www.w3schools.com/python/python_numbers.asp)
    [strings](https://www.w3schools.com/python/python_strings.asp)
    [booleans](https://www.w3schools.com/python/python_booleans.asp)
    [lists](https://www.w3schools.com/python/python_lists.asp)
    [dictionaries](https://www.w3schools.com/python/python_dictionaries.asp)
and others, but these will be enough for now 😊
Read them through carefully and do the relating exercises on W3Schools!
And in case it is not enough, and you would like to try out how can you solve problems with this knowledge, It is time to register on [CODEWARS](https://www.codewars.com/)
you can search there by language, coding level, and by tags. Go on, register and do at least 1 kudo every day from now.

    