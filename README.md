# Scroller

Scroller is a simple, lightweight scrolling library for React.

## Installation

To use Scroller in your project, first add it as a dependency with yarn or npm

```shell
# with yarn
yarn add sandypockets-scroller
```

or 

```shell
# with npm
npm install sandypockets-scroller
```

Add Scroller to the project file you want to use it in.

```javascript
// as a module
import { useScroller } from "sandypockets-scroller";
```

or 

```javascript
// as common js
const useScroller = require("sandypockets-scroller")
```

## Usage

A simple React.js example of a button triggering useScroller on click.

```javascript
import { useScroller } from "sandypockets-scroller";


export default function HomePage() {

  // Scrolls to 200px
  const scroller = useScroller({ y: 200, isSmooth: true })

  // height 3000 to illustrate scrolling
  return (
    <div style={{ height: 3000 }}>
      <button onClick={scroller}>
        trigger scroller onClick
      </button>
    </div>
  )
}
```

## Dependencies
- None

## Developer dependencies
  @babel/core `^7.17.5`
- @storybook/addon-actions `^6.4.19`
- @storybook/addon-essentials `^6.4.19`
- @storybook/addon-interactions `^6.4.19`
- @storybook/addon-links `^6.4.19`
- @storybook/react `^6.4.19`
- @storybook/testing-library `^0.0.9`
- babel-loader `^8.2.3`
- esbuild `^0.14.25`
- react `^17.0.2`
- react-dom `^17.0.2`

## Peer dependencies
- react `^17.0.2`
- react-dom `^17.0.2`
