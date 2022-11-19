# Redux
 
 ## Princaples of Redux

everything that change in your application including the data and the ui tree is contained in a single object called state or state tree

the state tree is Read-only, you can not modify or write to it. Instead you need to dispatch an action. There is nothing speacial about the action object exept you need a type prop to be defined

to describe state mutatuins, you have to write a function that takes the previous state of the app, the action being dispatched and returns the next state of the app.
This function has to be pure (same output for the same input) which called the Reducer.

## Redux Store

the store is the object that brings them together. 
The store has the following responsiblities:

* holds application state

* allows access to state via getState()

* allows state to be updated via dispatch(action)

* registers listeners via subscribe(listener)

* handles unregistering of listeners via the function returned by subscribe(listener)

* the store is created by passing the root reducer function to createStore()


## Data Flow

the data flow in redux follows these 4 steps:

* call store.dispatch(action)
* the redux store calls the reducer function you gave it
* the root reducer may combine the output of multiple reducers into a single state tree
* the redux store saves the complete state tree returned by the root reducer
