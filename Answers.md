1. What problem does the context API help solve?

Context API allows for a child component to access a value in a parent without prop drilling

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions: Send data from app to store

Reducers: App state change in response to actions

Store: Holds all information and manages the state

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

Component state is accessed by component and app state is state that is accessed at top of component all the way down

Compoentn state is used when you want to give a single component access to its data

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

Thunk allows us to use actions to return function instead of an object

1. What is your favorite state management system you've learned and this sprint? Please explain why!

I liked context seems the most user friendly


