---
sidebar_position: 1
---

# Numbers

A number is some entity representing the number of some items. Examples: two apples, five plates, ten books, one hundred dollars, and seven oranges. Every day we turn to numbers, sometimes without even noticing it.

In the early days, when people were taught to read and calculate, the number of objects was represented by sticks:

One item was represented as `|`

Two objects as `| |`

Three objects as `| | |`

As people became more literate, they realized that many items can not represent with sticks and replaced the sticks with numbers.

Today in mathematics, numbers are used to represent numbers. They are numbers 0, 1, 2, 3, 4, 5, 6, 7, 8, 9. Numbers scare away most children and students because they are associated with mathematics and “scary formulas”. In fact, there's nothing scary about it. Numbers are simply a set of symbols that are meant to represent numbers. In simplest terms, they are represent the number of items.

## Create a Page

Add **Markdown or React** files to `src/pages` to create a **standalone page**:

- `src/pages/index.js` -> `localhost:3000/`
- `src/pages/foo.md` -> `localhost:3000/foo`
- `src/pages/foo/bar.js` -> `localhost:3000/foo/bar`

## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at `http://localhost:3000/my-react-page`.

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at `http://localhost:3000/my-markdown-page`.
