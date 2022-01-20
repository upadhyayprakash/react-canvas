# `react-canvas` package

#### Summary

A react component to render canvas on a page and set of tools to sketch over it.

#### Get Started

1. Install from NPM repository

```bash
npm i @upadhyayprakash/react-canvas@latest
```

2. Import the `Cavnas` component

```javascript
import Canvas from "@upadhyayprakash/react-canvas";
```

3. Usage

```javascript
<Canvas
  toolbar={false} // true
  background="rgba(0, 0, 0, 0.2)" // "transparent"
  ...props
>
  {/* children */}
</Canvas>
```
check the `props` list for all the available options.

#### `props` list
- `toolbar`: `boolean (default: true)`
display canvas tools to interact. Eg. pencil, eraser, selection etc.
- `background`: `string`
set the canvas background. Default is `transparent`.
- `movable`: `boolean (default: false)`
drag the canvas within the app viewport
... add more
#### Copyright

Check the [LICENSE](https://github.com/upadhyayprakash/react-canvas/blob/ce075951bb9f4d6cbafd201c385a0a04ec842379/LICENSE) for copyright details.

#### Inspiration for Smooth Sketching

- Forking from: https://github.com/dulnan/lazy-brush
- Initial Reading: https://developpaper.com/canvas-advancement-how-to-draw-a-smooth-curve/
- Alternate Approach: https://jsfiddle.net/x2519uzf/
