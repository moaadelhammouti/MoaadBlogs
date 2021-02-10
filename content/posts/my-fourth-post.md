---
title: "STARTING WITH REACT"
date: 2021-02-10T11:06:54+01:00
draft: true
---

There are two primary ways to style react components

1. Inline styles with the style prop
2. Regular CSS with the className prop
   About the style prop:

- In HTML you’d pass a string of CSS:

```html
<div style="margin-top: 20px; background-color: blue;"></div>
```

- In React, you’ll pass an object of CSS:

```css
<div style={{marginTop: 20, backgroundColor: 'blue'}} />
```

Note that in React the {{ and }} is actually a combination of a JSX expression and an object expression. The same example above could be written like so:

```javaScript
const myStyles = {marginTop: 20, backgroundColor: 'blue'}
<div style={myStyles} />
```

Note also that the property names are camelCased rather than kebab-cased. This matches the style property of DOM nodes (which is a CSSStyleDeclaration object).
