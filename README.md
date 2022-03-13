# Scroller

An easy-to-use scrolling library

## Usage example

```
const scroller = useScroller(({ x: 5, y: 200, isSmooth: true }: Options));

scroller();

// Options
type Options = {
  x: number,
  y: number,
  isSmooth?: boolean,
};
```

