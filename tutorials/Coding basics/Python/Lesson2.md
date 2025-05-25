# Lesson 2: operations with basic variables

OK, now you can store some name, age, lists etc in variables. But what else can we do with them? It is useful in case we need, we can modify these variables. Lets see some simple operations

## Operations with integers

Integers mainly for calculating with them right? :)

You can add, substract, muliply etc.

[Main operations in python](https://www.w3schools.com/python/python_operators.asp) Try out all!

If you define a varialbe it not necessary remains the same during your program. Lets imagine a program which counts how many people has entered through the gate during the day, and how many left. After a successful day the two numberr equals right? :)

how it looks in programming?
```python
    people_at_the_beach = 0 # this is the start of the day.
```    
but later arrives the staff...
```python
    people_at_the_beach = 5 # you can simply give a new value to your variable
```
and later arrives your first guest:
```python
    people_at_the_beach +=1 # +=1 is the same as 
                            # people_at_the_beach = people_at_the_beach+1 or
                            # people_at_the_beach = 6 
                            # you can use any of them, depends on the code readibililty and use case which one you use, at this point it is enough, they are the same.
```
So once you assign a value to a variable it not necessary remains the same forever. If you want to be sure, that it not changes, you can create constants, which is marked with capital letter:
```python
    NUMBER_OF_LIFEGUARDS = 2 
```

Now its time to register to codewars.com, if you still not registered :) and practice a little every day from now.
On codewars you find Katas (kata is a Japanease word, meaning a short, repeated excercise to learn something alone) in 8 levels, 8 is the easiest, 1 is for challenge seakers :) Start with 8. :)
Some kata you can practice with:
[Even or odd](https://www.codewars.com/kata/53da3dbb4a5168369a0000fe)
[Keep hidrated](https://www.codewars.com/kata/582cb0224e56e068d800003c) -it deals with floats instead of integers! - Check [floats](https://www.w3schools.com/python/python_numbers.asp) if you not remember from Lesson1
