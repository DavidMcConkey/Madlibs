### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?

React is a free and opens-source front-end library for Javascript, used for building user interfaces based on components. It's widely used because components can be reused, making for easier implementation of features.

- What is Babel?

Babel is a javascript compiler. Converts ECMAScript code into backwards-compatible JS code.

- What is JSX?

JSX is an extension of JS and bascially lokos like HTML mixed with JS.

- How is a Component created in React?

A component is created by writing a function except it returns a JSX react element.

- What are some difference between state and props?

Props are used to pass data from a parent component to a child component, while state is used to manage data within a component.

- What does "downward data flow" refer to in React?

Data can only flow from a parent component down to a child component.

- What is a controlled component?

A controlled component is one controlled by React state.

- What is an uncontrolled component?

An uncontrolled component is one that maintains its own internal state.

- What is the purpose of the `key` prop when rendering a list of components?

The key prop gives the ability to control component instances.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

It is not recommended as it doesnt uniquely identify your elements.

- Describe useEffect. What use cases is it used for in React components?

This hook is used when you want your component to do something after render. Use cases can be state changes, on mount, when props change, and more.

- What does useRef do? Does a change to a ref value cause a rerender of a component?

This hook is commonly used to access or modify properties of DOM elements, like the value of an input or the scroll position of a container.

- When would you use a ref? When wouldn't you use one?

You would use a ref when you need to imperativbely call a function for a behavior that react doesn't allow you to control. You wouldn't use one on function components because they don't have instances.

- What is a custom hook in React? When would you want to write one?

A custom hook is a reusable piece of logic that can be used across different components. With the prefix of "use" these custom hooks are great for reducing redundancy in a react project by consolidating code.
