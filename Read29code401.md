1.  there is no way to pass props from a child component to a parent component. However, we can always pass around functions from the parent to child component. The child component can then make use of these functions. The function can then update the state in a parent component

2. it rendered normally if all child have a parent

3. sure

4. by react.Children



can use props. children on components that represent 'generic boxes' and that 'don't know their children ahead of time'.

Composition is the act of combining parts or elements to form a whole. Components are the UI building blocks in React applications, like pure functions are the building blocks of function composition.


React Router v4 is a pure React rewrite of the popular React package. Previous versions of React Router used configuration disguised as pseudo-components and could be difficult to understand. With v4, everything is “just components”.

The <Route> component is the main building block of React Router. Anywhere that you want to only render content based on the location’s pathname, you should use a <Route> element.


Route:

1.component — A React component. When a route with a component prop matches, the route will return a new element whose type is the provided React component (created using React.createElement).

2.render — A function that returns a React element 5. It will be called when the path matches. This is similar to component, but is useful for inline rendering and passing extra props to the element.

3.children — A function that returns a React element. Unlike the prior two props, this will always be rendered, regardless of whether the route’s path matches the current location.

 <Link> component to prevent relode the page

useRouteMatch
The useRouteMatch hook attempts to match the current URL in the same way that a <Route> would. It’s mostly useful for getting access to the match data without actually rendering a <Route>.


<BrowserRouter>
A <Router> that uses the HTML5 history API (pushState, replaceState and the popstate event) to keep your UI in sync with the URL.


<HashRouter>
A <Router> that uses the hash portion of the URL (i.e. window.location.hash) to keep your UI in sync with the URL.





