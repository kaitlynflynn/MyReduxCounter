# My Redux Counter
Practicing how to create a Redux Counter and connecting it to React Components. This is a simple application consisting of increments and decrement buttons for our counter. 

## Topics Covered in this Exercise
* [Immutability in JavaScript](https://www.sitepoint.com/immutability-javascript/)
* [Redux](http://redux.js.org/docs/basics/)
* [Actions](https://redux.js.org/basics/actions)
* [Reducers](https://redux.js.org/basics/reducers)
* [The central store](https://redux.js.org/api/createstore)
* [Connecting React components to Redux](https://redux.js.org/basics/usage-with-react)

## Definitions: 
* **Redux:** Redux is an open-source JavaScript library for managing application state. It is most commonly used with libraries such as React or Angular for building user interfaces.

* **Actions:** Actions are payloads of information that send data from your application to your store. They are the only source of information for the store. You send them to the store using `store.dispatch()`

* **Reducers:** Reducers specify how the application's state changes in response to actions sent to the store. Remember that actions only describe what happened, but don't describe how the application's state changes.

* **The Central Store:** In the previous definitions, we defined the actions that represent the facts about _“what happened”_ and the reducers that update the state according to those actions. The **Store** is the object that brings them together.

## My Redux Counter Features
* Increment button increments counter by 1. 
* Decrement button decrements counterby 1.
* Demonstrating how Redux is hooked up to a React App. 

## How to Run App
1. From your terminal, run `yarn` at the `src` (root) directory which will install the needed `node modules`.
2. Once this is complete, run `yarn start`.
