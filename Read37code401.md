we use Redux for a large Application that state change frequently and useContext for small app and small settings
to  determines changes to an application's state 
functions that change state in switch case by Type 
to dont get an Error by other used for state 

mmutable state is state that cannot be changed

time-travel debugging and to view Redux actions.

action creator is merely a function that returns an action object.

A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.

Dispatches an action. This is the only way to trigger a state change.




combineReducers takes an object full of slice reducer functions, and creates a function that outputs a corresponding state object with the same keys. This means that if no preloaded state is provided to createStore, the naming of the keys in the input slice reducer object will define the naming of the keys in the output state object. The correlation between these names is not always apparent, especially when using ES6 features such as default module exports and object literal shorthands.











