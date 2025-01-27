# React 19 useEffect Hook Runs Twice Bug

This repository demonstrates a bug where the `useEffect` hook in React 19 runs twice unexpectedly when using an empty dependency array `[]`. This is unexpected behavior, as the empty array should signify that the effect should only run once on mount. The bug is showcased in `bug.jsx`. A potential solution is provided in `bugSolution.jsx`.