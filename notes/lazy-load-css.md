---
title: Lazy load CSS
tags:
  - css
---

From https://www.filamentgroup.com/lab/load-css-simpler/

```html
<link rel="preload" href="/path/to/my.css" as="style" />
<link
  rel="stylesheet"
  href="/path/to/my.css"
  media="print"
  onload="this.media='all'"
/>
```