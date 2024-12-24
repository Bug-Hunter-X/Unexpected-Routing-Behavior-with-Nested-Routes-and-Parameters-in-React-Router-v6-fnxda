# Unexpected Routing Behavior with Nested Routes and Parameters in React Router v6

This repository demonstrates a bug in React Router v6 where nested routes with parameters exhibit unexpected routing behavior. Routes may fail to render correctly or redirect unexpectedly.  The `bug.js` file shows the problematic code, and `bugSolution.js` provides a solution.

## Problem
The issue arises when combining nested routes and route parameters in React Router v6.  The expected behavior is not always achieved, leading to incorrect rendering or unexpected redirects.

## Solution
The solution involves careful restructuring of the routes, potentially using `useParams` to access parameters correctly and ensuring proper nesting and parameter handling.

## Steps to Reproduce
1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npm start` to start the development server.
4. Navigate to different routes and observe the unexpected behavior.
