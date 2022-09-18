## Quick Start

:::tip{title="Compatibility Note"}
Vite requires Node.js version 14.18+, 16+. However, some templates require a higher Node.js version to work, please upgrade if your package manager warns about it.
:::

You can modify the `markdown` code like writing a document to view your component effect in real time.

---

#### Welcome to use [**Vitdoc**](https://vitdocjs.github.io)

```tsx
import { Title as Component } from '.';
import React from 'react';
import ReactDOM from 'react-dom';

ReactDOM.render(
  <div style={{ display: 'flex', flexDirection: 'column' }}>
    <Component
      title="Training Material"
      subTitle="Ensure that you meet our campaign criteria.\n Click on the respective image below to unlock tips on how to soar this 12.12 !"
    />
    <Component
      title="PREPARE FOR 12.12 WITH 6 KEY FOCUS"
      subTitle="Ensure that you meet our campaign criteria.<br /> Click on the respective image below to unlock tips on how to soar this 12.12 !"
    />
    <Component
      theme={{ isMobile: true }}
      title="PREPARE FOR 12.12 WITH 6 KEY FOCUS"
      subTitle="Ensure that you meet our campaign criteria.<br /> Click on the respective image below to unlock tips on how to soar this 12.12 !"
    />
  </div>,
  mountNode,
);
```
