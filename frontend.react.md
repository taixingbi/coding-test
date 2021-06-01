#### 1. What are the advantages of using React?
MVC is generally abbreviated as Model View Controller.

#### 2. **Use of Virtual DOM to improve efficiency**       
React uses virtual DOM to render the view. As the name suggests, virtual DOM is a **virtual representation of the real DOM**. Each time the data changes in a react app, a new virtual DOM gets created. Creating a virtual DOM is much faster than rendering the UI inside the browser. Therefore, with the use of virtual DOM, the efficiency of the app improves.

#### 3. **Gentle learning curve**       
React has a gentle learning curve when compared to frameworks like Angular. Anyone with little knowledge of javascript can start building web applications using React.

#### 4 **SEO friendly**     
React allows developers to develop engaging user interfaces that can be easily navigated in various search engines. It also allows server-side rendering, which boosts the SEO of an app.

#### 5 **Reusable components**     
React uses **component-based architecture** for developing applications. **Components are independent** and reusable bits of code. These components can be 
**shared** across various applications having similar functionality. The re-use of components increases the pace of development.   

#### 6 **Huge ecosystem of libraries**
React provides you the **freedom to choose the tools, libraries, and architecture** for developing an application based on your requirement

#### 7 What is JSX?
JSX stands for JavaScript XML.
It allows us to **write HTML inside JavaScript and place them in the DOM** without using functions like appendChild( ) or createElement( ).

#### 8 What are the differences between functional and class components?
* Before the introduction of Hooks in React, functional components were called **stateless** components and were behind class components on feature basis. 
* After the introduction of Hooks, functional components are equivalent to class components.

#### 9 What is the virtual DOM? How does react use the virtual DOM to render the UI?
As stated by the react team, virtual DOM is a concept where a **virtual representation of the real DOM** is kept inside the memory and is synced with the real DOM by a library such as ReactDOM.

#### 10. What are the different lifecycle methods in React?
controlled Components | uncontrolled Components
------------ | -------------
form data is handled by a **React component** | form data is handled by the **DOM itself**
writing an event handler for every state update | use a ref to get form values from the DOM


#### 10. What are the different lifecycle methods in React?
Each component in react goes through three phases: Mounting, Updating, and Unmounting.


