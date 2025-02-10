# React useEffect Infinite Loop Bug
This example demonstrates a common mistake in using the React `useEffect` hook, resulting in an infinite loop.  The `setInterval` function is called repeatedly, updating the state and causing the component to re-render constantly.  The solution involves correctly using the dependency array to control when the effect runs.