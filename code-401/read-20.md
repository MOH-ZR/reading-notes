# Component Based UI

## Review, Research, and Discussion
**Name 5 Javascript UI Frameworks (other than React)?**
1. Angular
2. Vue
3. Sencha
4. Backbone.js
5. Vaadin  

**What’s the difference between a framework and a library?**  
A library is like going to Ikea. You already have a home, but you need a bit of help with furniture. You don’t feel like making your own table from scratch. Ikea allows you to pick and choose different things to go in your home. You are in control.

A framework, on the other hand, is like building a model home. You have a set of blueprints and a few limited choices when it comes to architecture and design. Ultimately, the contractor and blueprint are in control. And they will let you know when and where you can provide your input.


**Rendering**: it is a process used in web development that turns website code into the interactive pages users see when they visit a website.  
**Templates**:  It is a form, mold, or pattern used as a guide to making something.  
**State**: state is how something is; its configuration, attributes, condition or information content.

## React

The 'Hello world' react version
```js
    ReactDOM.render(
        <h1>Hello world!</h1>
        document.getElementById('root);
    );
```

The building blocks of React apps: 
* elements: the samllest building block of React apps and describe what you want to see on the screen.
* components

**Introducing JSX**

JSX stands for JavaScript XML. JSX allows us to write HTML in React and makes it easier to write and add HTML in React.  
JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  and/or appendChild() methods. for example:

JSX
```js
    const myelement = <h1>I Love JSX!</h1>;
    ReactDOM.render(myelement, document.getElementById('root'));
```

Without JSX:
```js
    const myelement = React.createElement('h1', {}, 'I do not use JSX!');
    ReactDOM.render(myelement, document.getElementById('root'));
```
