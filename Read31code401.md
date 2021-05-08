1. beacause we use browser route that we can make milti pages without create milty html pages
 
2. Inside the <BrowserRouter />, outside a <Route />

3.  props. children does is that it is used to display whatever you include between the opening and closing tags when invoking a component. 


 composition is a natural pattern of the component model. It's how we build components from other components, of varying complexity and specialization through props. Depending on how generalized these components are, they can be used in building many other components.

Children allow you to pass components as data to other components, just like any other prop you use. The special thing about children is that React provides support through its ReactElement API and JSX. XML children translate perfectly to React children!

 hash-based routing is using the anchor part of the URL to simulate different content. For example http://site.com/#/products/list leads to displaying a list of products.

link-state routing is that every node constructs a map of the connectivity to the network, in the form of a graph, showing which nodes are connected to which other nodes. Each node then independently calculates the next best logical path from it to every possible destination in the network.


When we try to solve these use cases with components alone, we usually end up with:
Huge components that are hard to refactor and test.
Duplicated logic between different components and lifecycle methods.
Complex patterns like render props and higher-order components.

If Hooks still don’t seem compelling to you, I can totally understand it. I still hope that you’ll give them a try on a small pet project and see if that changes your opinion. Whether you haven’t experienced the problems Hooks solve, or if you have a different solution in mind, please let us know in the RFC!

 A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We’ll learn other Hooks later.


