1. What problem does the context API help solve?

    Context API solves the issue of passing state from parents to children can become cumbersome after a while by storing the data in the context object.

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    Actions contain information that can be passed on to the reducer as an argument.

    Reducers are functions that allow for easy state management that take two arguments and return the new state from those arguments.

    The store is a state tree that can not be changed directly, to be able to change the information from the store you must change copies of the information with actions and reducers.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

    The difference between Application and Component state is that Application state is immutable while Component state is mutatable and is generally better to use application state in larger projects while Component state is well suited for small scale projects.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

    Redux-thunk is a middleware that allows us to do asynchronous operations with Reducers in Redux and changes action-creators to let us make API calls from the action-creators.

1. What is your favorite state management system you've learned and this sprint? Please explain why!

    While I originally favored context API, redux as slowly become my new favorite state management system, this is due to how much the management is broken down which makes it much easier for me to figure out and use.