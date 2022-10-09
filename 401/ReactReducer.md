## React Reducer

useReducer its an alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method, seReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks

in useeffect The second param is an array of variables that the component will check to make sure changed before re-rendering, and if we pass an empty array [] , it just renders the component only once like componentDidMount.

we could combine the all the states into one state object and then we could do one setState call and there will only be one render.

useState and setState both are asynchronous. They do not update the state immediately but have queues that are used to update the state object. This is done to improve the performance of the rendering of React components.

State Hook: Hook state is the new way of declaring a state in React app. Hook uses useState() functional component for setting and retrieving state.

Component Lifecycle: Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are: Mounting, Updating, and Unmounting.
