# assignment

State
The state is an updatable structure that is used to contain data or information about the component and can change over time. The change in state can happen as a response to user action or system event. It is the heart of the react component which determines the behavior of the component and how it will render. A state must be kept as simple as possible. It represents the component's local state or information. It can only be accessed or modified inside the component or by the component directly.
Props
Props are read-only components. It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. It allows passing data from one component to other components. It is similar to function arguments and can be passed to the component the same way as arguments passed in a function. Props are immutable so we cannot modify the props from inside the component.

UseState
Const [state,setState] = useState(initialState);

Returns a stateful value,and a function to update it.During the initial render, the returned state(state) is the same as the value passed as the first argument (initialState). The setState is used to update the state. It accepts the new state value and enqueues a re-render of the component.
setState (newState);
During subsequent re-renders, the first value returned by useState will always be the most recent state after applying updates.


How map works in React ?
In React, the map method is used to traverse and display a list of similar objects of a component. A map is not a feature of React. Instead, it is the standard JavaScript function that could be called on an array. The map () method creates a new array by calling a provided function on every element in the calling array.



How Filter works in React?
Filtering in React is pretty much what it says it is. It’s the process of looping through an array and including or excluding elements inside that array based on a condition that you provide.
The caveat here is that we’re not actually filtering using React. Filter is a JavaScript function that we can perform on an array type object.

How reduce works in React?	
The Reduce method, as the name implies, reduces the value of an array to a single value by applying the reduce function to each element of the array.
arr.reduce (callback[, initialValue]
Let’s take a look at some important concepts of React before getting into the details of how to render the array using the aforesaid functions.

