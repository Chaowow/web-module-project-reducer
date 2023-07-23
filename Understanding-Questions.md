# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 
...
The onClick handler action is fired 

addOne inside of ./actions/index.js creates the package 

which then goes inside of our reducer

takes the state and adds one to it

then our application is re-rendered with the new total

* TotalDisplay shows the total plus 1.
