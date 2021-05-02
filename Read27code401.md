1. You don't necessarily need a static server in order to run a Create React App project in production. It also works well when integrated into an existing server side app.

2.You can test React components similar to testing other JavaScript code. ... Iteration speed vs Realistic environment: Some tools offer a very quick ... change and seeing the result, but don't model the browser behavior precisely. ... How much to mock: With components, the distinction between a “unit” and “integration” 

3.npm run build runs the script "build" and created a script which runs your application

4.Composition

The key feature of React is composition of components. Components written by different people should work well together. It is important to us that you can add functionality to a component without causing rippling changes throughout the codebase.
Laying the foundation of a scalable architecture in large applications is not as easy as it seems. You could either end up going south or things may not work out as planned. 
architicture

Even worse, there can be times when you need to reinvent the wheel only to find out you’re still stuck in the middle of nowhere.

Behaviour-Driven Development (BDD) is a collaborative approach to software development that bridges the communication gap between business and IT. BDD helps teams communicate requirements with more precision, discover defects early and produce software that remains maintainable over time.

Acceptance test driven development to develop a web application through a real example. As you may know, the hardest thing of design an good example is that you have to balance the simplicity and complexity at the same time.

Mounting is the phase in which our React component mounts on the DOM (i.e., is created and inserted into the DOM). This method is called just before a component mounts on the DOM or the render method is called. After this method, the component gets mounted.

build: The output of the previous process, an artifact which is produced during the build process that includes interpreted source code and compiled assets. Deployment: Process of putting (deploying) the BUILD to a server.

Workings of `setState()`
setState() is the only legitimate way to update state after the initial state setup. Let’s say we have a search component and want to display the search term a user submits.
A href
<a href="#" onClick={handleClick}>
buttons
 <button onClick={this.handleClick}>
forms
<form onSubmit={this.handleSubmit}>
