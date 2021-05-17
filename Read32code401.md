1- useMemo() to improve performance , useReducer() for multiple and ambigiouse  state

2-The prefix property sets or returns the namespace prefix of a node.

3- make like a model for the codes that we want to re-use it 

4-sure because the code will be more readable and shorter

5- by using useEffect to prevent infinite loop or use call back function

A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.

Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.
const ThemeContext = React.createContext('light');

react-providers - A small library that creates a centralized place to store (like Redux store) your context components and HOC to use it. Automatically resolves dependencies between your context components.
react-context-global-state - A wrapper library around the Context API to define global state without explicitly using class components.
observed-bits - A tiny library that helps to avoid unnecessary re-renders of all Consumers.
folio - A dynamic form manage form global state and CSS grid using context.
react-combine-reducer - Function that merge context providers in ease. Supports constate and unstated-next in a simple way.
