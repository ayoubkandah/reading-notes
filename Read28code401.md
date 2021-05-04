1. In React we can access the child's state using Refs. we will assign a Refs for the child component in the parent component. then using Refs we can access the child's state. Creating Refs Refs are created using React

2.props enable you to pass variables from one to another component down the component tree. In the previous example, it was only a string variable. But props can be anything from integers over objects to arrays.

3. by sending a state from app.js and take it from another component that need this state


Props are arguments passed into React components. Props are passed to components via HTML attributes.

The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.

Application State (also known as Program State) represents the totality of everything necessary to keep your application running. When we refer to application state we are normally referring to the state of the program as it exists in the contents of its memory.

Mounting
Since class-based components are classes, hence the name, the first method that runs is the constructor method. Typically, the constructor is where you would initialize component state.

Next, the component runs the getDerivedStateFromProps. I’m going to skip this method since it has limited use.

Now we come to the render method which returns your JSX. Now React “mounts” onto the DOM.


Containment
Some components don’t know their children ahead of time. This is especially common for components like Sidebar or Dialog that represent generic “boxes”.

{props.children}

Props and composition give you all the flexibility you need to customize a component’s look and behavior in an explicit and safe way. Remember that components may accept arbitrary props, including primitive values, React elements, or functions.




