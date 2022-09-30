# Colors

```js script
import { html } from 'lit';
import '@divriots/dockit-core/css-showcases/dockit-css-showcases.define.js';
import './styles.css';
import '~/tokens/variables.css';
```

## Core

### Blue

```js story
export const blue = () => html`
  <dockit-css-showcases
    css-props-prefix="--cds-core-color-blue"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

