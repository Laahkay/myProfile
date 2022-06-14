---
Layout:
Title: "Pass an Array as Props"
Date: "2022-06-14"
---

# Introduction 

 How arrays can be passed as props. To pass an array to a JSX element, it must be treated as JavaScript and wrapped in curly braces.

 # BODY 

 It is where i have been ask to write a code that will print the things that i would be doing today and tomorrow so all i neeeded to do is to pass some props so we have been given a method to that which is (props) => <p>{props.colors.join(', ')}</p> from freecodecamp so i was able to understand it because it is where we have to replace color with task because is the one that holds the the prop so the props  should have the child component when we render is to the child would hold the the tasks that i would be showing should be 3 on each list of today and tomorrow here is the answer that i have written to pass the test watch below 

 frst thing we have to return <p>{props.task.join(', ')}</p>

 and secondly we have to write our list lke this  <List task={["walk", "go out","code"]}/>
        <h2>Tomorrow</h2>
        <List task={["play", "workout",'party']}/>

Thats how i was able to pas the test and got a better understanding of the code.

# CONCLUSION 

I was a very goood practice today that got me thinking all this time but i really like doing React because it more understandable to me so i had it on mind as alway. THank you 