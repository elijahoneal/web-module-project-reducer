# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* the onClick event dispatches the addOne action
* the addOne action calls the ADD_ONE type in the reducer function
* the reducer function adds 1 to the current state
...

* TotalDisplay shows the total plus 1.
