### React Js Interview Questions

<details>
<summary><strong>What is a Virtual DOM and Diff between realDom and VirtualDom</strong></summary>
<p>

The Virtual DOM is a lightweight, in-memory representation of the actual DOM (Document Object Model) in a web page

The process of updating in React
1. The ReactDOM.render() renders the elements on the screen on the first load by creating the real and virtual DOM trees.

2. Any change to an element (such as a key press or button click) leads to a notification sent to the virtual nodes for a state change. If any property of the node is altered, it updates itself.

3. React compares the updated virtual DOM with the real DOM and updates the real DOM accordingly. This process is known as reconciliation. This is done using a heuristic algorithm known as the Diffing Algorithm.

4. The updated real DOM is rendered on the screen.

</p>
</details>

<details>
<summary><strong>What is fragment
?</strong></summary>
<p>

In React, a Fragment is a way to group multiple children elements without adding an extra DOM element to the output. It's a lightweight wrapper that doesn't create an additional DOM node in the rendered HTML, which can be useful in situations where you need to return adjacent JSX elements without enclosing them in a parent HTML element.

Here's how you can use a Fragment in React:

```
import React from 'react';

function MyComponent() {
  return (
    <React.Fragment>
      <h1>Hello</h1>
      <p>React Fragments</p>
    </React.Fragment>
  );
}

export default MyComponent;

```
Alternatively, you can use the shorthand syntax for fragments introduced in React 16.2:

```
import React from 'react';

function MyComponent() {
  return (
    <>
      <h1>Hello</h1>
      <p>React Fragments</p>
    </>
  );
}

export default MyComponent;

```

</p>
</details>

<details>
<summary><strong></strong></summary>
<p>



</p>
</details>
