# React Router v6 Unexpected Route Matching

This repository demonstrates an uncommon bug in React Router v6 related to route path matching.  When one route's path is a substring of another, the order of routes within the `<Routes>` component significantly impacts which route is matched. This can lead to unexpected routing behavior.

The `bug.js` file shows the problematic code.  The `bugSolution.js` file presents a solution.