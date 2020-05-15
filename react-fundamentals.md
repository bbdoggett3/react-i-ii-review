### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
React is a Javascript library for building user interfaces. It is component based which makes rendering the page quick and efficient. 

2.  What is create-react-app?
It creates all the dependecies for you so you are ready to work in react and begin coding.

3.  What is Component Based Architecture?
Component turns raw data in rich HTML and is built from props and state. It can be in state or stateless. Code is spilt into chunks called components. It makes code highly reuseable and easy to debug.


4.  What is JSX?
JSX is an XML/HTML-like syntax used by React that extends ECMAScript so that XML/HTML-like text can co-exist with JavaScript/React code

5.  What is the virtual DOM?
A virtual copy of the browser DOM stored in memory that React users to identify and target changes.
This process is changed in the virtual DOM and then changed in the actual DOM this is called reconciliation.

6.  What is unidirectional (one-way) data flow?
Data flows that goes from parent to child.

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `npx create-react-app my-app`
It creates the React project with the dependcies package from react and names that project 'my-app.' 

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?
  *Fork it
  *Clone it
  *Navigate to the directory of your react app
  *Run npm install 

9.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.
It is passed through props

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
