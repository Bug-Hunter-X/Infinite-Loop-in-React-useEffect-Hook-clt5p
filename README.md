# React useEffect Infinite Loop Bug
This repository demonstrates a common error in React applications involving the `useEffect` hook.  The bug causes an infinite loop because the state is updated within the `useEffect`'s callback, triggering a re-render and another update to the state, creating a never-ending cycle. 

The solution demonstrates the correct usage of `useEffect`, using the dependency array to control updates and preventing unintended infinite loops.