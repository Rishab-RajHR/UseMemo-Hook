useMemo is a React Hook used to optimize performance by memoizing expensive calculations.

It prevents unnecessary recalculations on every render.

The memoized value is recomputed only when dependencies change.

Syntax: useMemo(() => computeValue, [dependencies]).

Useful for heavy computations like filtering, sorting, or complex calculations.

Helps reduce re-render cost in functional components.

Should not be used for side effects (use useEffect instead).

Overusing useMemo can make code harder to read.

Best practice: use it only when performance issues are noticeable.
