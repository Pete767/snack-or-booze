### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
So you can change URL with single-page app
- What is a single page application?
An app that never refreshes (just the components)
- What are some differences between client side and server side routing?
Client does not need to keep making requests to server.
- What are two ways of handling redirects with React Router? When would you use each?
Import Redirect or don't use exact path
- What are two different ways to handle page-not-found user experiences using React Router? 
ing a <Route> with a path of "*" or a component like <Switch> or a custom <Route> component that checks for the existence of a valid route 
- How do you grab URL parameters from within a component using React Router?
useParams
- What is context in React? When would you use it?
When a nested component can access variables without having to decalre through every single nested component
- Describe some differences between class-based components and function
  components in React.
Class-based components in React are ES6 classes that extend from React.Component and have a state object, allowing for the use of lifecycle methods. Function components, on the other hand, are simpler and more concise, written as JavaScript functions.
- What are some of the problems that hooks were designed to solve?
Before hooks, React didn’t have a basic way of extracting and sharing logic