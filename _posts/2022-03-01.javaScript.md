---
Layout:
Title: "Functional Programming"
Date: "2022-03-01"
---

# introduction

I have learned about the Functional Programming is another popular approach to software development. In Functional Programming, code is organized into smaller, basic functions that can be combined to build complex programs,

# Body

In this curriculam i have learned about how to create solated functions - there is no dependence on the state of the program, which includes global variables that are subject to change and about the pre functions where by the input give the same output using the (prepareTea and getTea )functions to define for us and also how to understand fucntion programming Terminilogies in this part it where by the The FCC Team had a mood swing and now wants two types of tea: green tea and black tea. General Fact: Client mood swings are pretty common heavenly sake there is some method we use which are as follows Map and for loop that gives directions to iterate over the indices of an array and it involve avoid mutation and side effects using functional programming but then we use the methods of splice and tabClose() where by the Splice changes the original array when it is called and passing a function its also included, here some example

 global_list = []
def append_to_list(x):
    global_list.append(x)

The good news is that there is an easy fix: being honest about what the function takes as an input. This is much better like this one bellow

newlist = []
def append_to_list3(x, some_list):
    some_list.append(x)
append_to_list3(1,newlist)
append_to_list3(3,newlist)
newlist

Functional programming is writing pure functions And a function without side effects is a pure function. A very simple definition of functional programming is this: writing a program only in pure functions. Pure functions never modify variables, but only create new ones as an output.

# Conclusion

The programming function it is a veru unique because it teach how to pass a function using different methods map() , split(),splice(),global list.