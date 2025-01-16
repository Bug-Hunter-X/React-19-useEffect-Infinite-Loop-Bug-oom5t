# React 19 useEffect Infinite Loop Bug

This repository demonstrates a common bug in React 19 involving the `useEffect` hook.  The bug occurs when the dependency array is omitted or incorrectly specified, leading to an infinite loop.  The solution involves correctly defining the dependency array to control when the effect runs.