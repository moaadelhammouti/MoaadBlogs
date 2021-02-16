---
title: "ReactDOM ?"
date: 2021-02-14T23:38:17+01:00
draft: true
---

what is the role of React and what is the role of ReactDOM ?

```JSX
 ReactDOM.render(<h1>Hello world</h1>, document.getElementById('app'));
```

ReactDOM is the name of a Javascript library. The library contains several React methods, all of which deals with the DOM. The above code shows us one of the most important methods of ReactDOM: ReactDOM.render().
It is one of the common ways of rendering JSX expressions to the screen. ReactDOM.render() carries two argument. The first is the JSX expression which in this case in the above code is Hello world while the second argument document.getElementById(‘app’) is the element where the first argument is appended on. Allow me to explain; we’ve learned the first argument makes the JSX expression render on the screen. But where on the screen should the first argument appear. It is appended in the element selected in the second argument; in this case, Hello world appends in the element selected from document.getElementById(‘app”).
so we can say that the role of React is for creating elements and the role of ReactDOM is to take those elements and put them on the page.
