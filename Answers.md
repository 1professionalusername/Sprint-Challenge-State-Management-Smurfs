What problem does the context API help solve?

Context API helps cut down on prop drilling. It allows you to share props or state with an indirect child or parent.


In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

actions-Events triggered by the UI, they're telling reducers what to do and are passing necessary info.
reducers- Reducers specify how the application's state changes in response to actions sent to the store. 
store- Holds app state and allows state to be changed.
Store is known as a single piece of truth because it passes the global state 
around to components which can then use the pieces of state they need. 

What is the difference between Application state and Component state? When would be a good time to use one over the other?

Application state is global and component state is local. If I had lots of components in
my app, I would use app state and if I only had a few I would use component.

Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

Redux-thunk is middleware that allows redux to run asynchronously. We can now make API calls from our action creators.


What is your favorite state management system you've learned and this sprint? Please explain why!

I liked context originally, but now I like Redux the best. 
There are a lot of moving pieces, but I know it will be useful for large applications.