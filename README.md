# React Router v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router v6.  The catch-all route is intended to render a 404 Not Found component when a user navigates to a non-existent path, however, it may not always work as expected. This example shows how a seemingly correct implementation might fail and provides a solution.

## Problem

The `App.js` file contains a React Router v6 setup with a catch-all route. Despite this, navigating to a route not defined in the `Routes` component doesn't render the NotFound component.