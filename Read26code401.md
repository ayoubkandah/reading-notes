1.
Angular
Vue.js
Ember.js
Node.js
Polymer

2.When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. When you use a framework, the framework is in charge of the flow. It provides some places for you to plug in your code, but it calls the code you plugged in as needed.

The term “render prop” refers to a technique for sharing code between React components using a prop whose value is a function.

templates are sets of ready-to-use parts of code built using React technology for the development of dynamic user interfaces. React templates may contain full-fledged pages with a pre-built design, component compositions, stand-alone components, styling (like fonts, colors theme effects, background styles, icons), plugins, widgets, libraries. 

The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.


react simple ex.

ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);

JSX

function getGreeting(user) {
  if (user) {
    return <h1>Hello, {formatName(user)}!</h1>;
  }
  return <h1>Hello, Stranger.</h1>;
}




ReactDOM.render(element,where render the element). to rendering elements



