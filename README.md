# React Router Dom v6 Catch-all Route Issue

This repository demonstrates a common issue in React Router Dom v6 where a catch-all route (`/*`) interferes with other routes, causing the catch-all route to be triggered even when a more specific route should be matched.  The problem is that the catch all route must be placed last in the routes array.

## Solution
The solution involves re-ordering the routes so the catch-all is the last route.