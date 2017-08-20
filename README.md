Tutorial that I followed is [here](https://github.com/huffleman51/js-stack-from-scratch/blob/master/tutorial/08-bootstrap-jss.md#readme).

# What I learned in this module

1. Twitter Bootstrap is a library of UI components.
1. There are 2 options to integrate Bootstrap in a React app. Both have their pros and cons:
  * Using the official release, which uses jQuery and Tether for the behavior of its components.
  * Using a third-party library that re-implements all of Bootstrap's components in React, like React-Bootstrap or Reactstrap.
  * This tutorial decided to use Bootstrap which used jQuery and Tether
1. I copied and pasted a bunch of code without really understanding what is going on. This is one thing that I don't like about this tutorial.
1. Added Bootstrap code to style the pages and add a navigation bar
1. The current state of CSS
  * Nothing settled, there is no standard way to go, no standard stack.
  * They all do it well, which is the problem, there is no clear winner, it's a big mess.
  * The cool React kids tend to favor React inline styles, CSS-in-JS, or CSS Modules approaches though, since they integrate really well with React and solve programmatically many issues that regular CSS approaches struggle with.
  * My personal suggestion would be to use React inline styles for common styles (that's also what you have to use for React Native), and use a CSS-in-JS library for things like :hover and media queries.
1. JSS is a CSS-in-JS library to write your styles in JavaScript and inject them into your app.
  * JSS can be used via react-jss, a library that is convenient to use with React components.
  * JSS can render styles on the server for the initial rendering.
  * On the client side, unlike React inline styles, JSS uses classes. You pass styles to injectSheet and the CSS classes end up in the props of your component.

