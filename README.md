# React setInterval Memory Leak

This repository demonstrates a common mistake when using `setInterval` within a React component's `useEffect` hook: forgetting to clear the interval when the component unmounts.  This leads to memory leaks and can cause unexpected behavior.

The `bug.js` file shows the problematic code. The `bugSolution.js` file provides the corrected version with a cleanup function to clear the interval.