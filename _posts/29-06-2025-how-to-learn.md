---
layout: post
title:  How To Learn
categories: [HTML,Code]
excerpt: In this mini blog, I'll be putting in my way of learning a new framework/library. I'm about to learn react library and it's Let's see how it goes.  
---

## Steps to learn

1. Choose a topic -> How should I learn react framework in a very short span of time like a few days. My aim is to get ready with interview questions and build a basic web app.
2. Explain the tech to a beginner
3. Build this and deploy the working demo.

* function == component
it returns the HTML in form of JSX.
props is used to pass data.

* hooks is function to return a value or also a function to change the value.

* It has huge number of libraries for various tasks/features
* know react? react+native = app developer
* JSX ~ HTL, a markup syntax
* HTL is a templating language to separate presentation logic from business logic.

### jQuery & react

Both approaches dynamically manipulates the DOM and generates content. Both can be used to create reusable code snippets or components.

### jQuery Vs react

jQuery directly manipulates DOM, attaches events, directly use utility functions to iterate, conditional execution, whereas react manipulates virtual DOM and uses native JS for all tasks. easier to manage state change, large dynamic components on the webApp.

### Hooks

Before Hooks, we'd functional(simple, stateless for rendering UI) and class(manage state) components. Hooks introduced a way to add state and side effects to functional components. To easily manage state, side effects and much more.

* State : refers to the data that changes within a component. when state changes, react re-renders the component
* Side effects : actions that can affect other components and can't be done during rendering like, API calls, event handling, updating DOM directly. useEffect runs after the component has rendered. 

### Props

Props (properties) are like function arguments passed to a component

### Tic-tac-toe tut

* an important point to ponder upon is lifitng state up. This means moving the state management from one component to another when refactoring, up or down. If tho child component need to share state information, the parent can pass that state back down to the children via props.     