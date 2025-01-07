# React Native: TypeError: Cannot read properties of undefined (reading '...property...')

This repository demonstrates a common error in React Native applications: attempting to access a property of a null or undefined object. This typically arises when working with asynchronous operations (like fetching data from an API) where the data might not yet be available.

The `bug.js` file shows the problematic code, causing the error. The `bugSolution.js` file provides a solution using optional chaining and nullish coalescing to handle the potential absence of data gracefully.