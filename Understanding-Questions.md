# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 
2. The event handler attached to the instance of the button with value 1, made with the CalcButton constructor, is fired.
3. handleClick event instantiates the useReducer setter, dispatch.
4. dispatch uses the addOne action creator, located in our actions folders index file, to tell reducer what to do. 
5. action creators simplify the input of reducers action parameter, so when reducer pops, we have the (if/else/else if) SWITCH handles which reducer function we want to use. in this case, addOne.
6. addOne creates a spread of our immutable state created within the reducer file, and mutates whichever key is specified.


* TotalDisplay shows the total plus 1.
