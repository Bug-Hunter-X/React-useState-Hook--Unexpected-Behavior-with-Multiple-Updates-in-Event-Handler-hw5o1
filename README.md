# React useState Hook: Unexpected Behavior with Multiple Updates in Event Handler

This repository demonstrates an uncommon bug related to React's `useState` hook.  When the `setCount` function within the event handler is called multiple times rapidly, the updates may not be processed correctly, resulting in the counter not incrementing by the expected amount.  This is due to how React batches state updates. 

The `bug.js` file shows the problematic code. The `bugSolution.js` file provides a corrected version.