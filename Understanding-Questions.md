# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 
    1. goes to the handleAddOne function
    2. from there, addOne() goes to actions
    3. from actions, returns {type:ADD_ONE} back to app.js
    4. then dispatches it to the reducer
    5. changes the state to increase by 1

...

* TotalDisplay shows the total plus 1.
