# React Native useState Hook Not Updating Nested Object

This repository demonstrates a common issue encountered when using the `useState` hook in React Native with nested objects.  The problem arises from React's shallow comparison, which fails to detect changes within nested objects if the outer object reference remains unchanged.

The `nestedObjectBug.js` file shows the incorrect implementation where modifying a nested object doesn't trigger a re-render. The `nestedObjectSolution.js` file provides the correct solution using the spread operator to create a new object with updated values.

## Setup

To run this example, make sure you have Node.js and npm installed. Then, clone this repository and run:

```bash
npm install
npm start
```