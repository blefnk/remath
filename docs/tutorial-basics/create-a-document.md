---
sidebar_position: 2
---

# Operations

The basic operations used in mathematics are addition, subtraction, multiplication, and division.

In addition to these operations, there are also ratio operations such as: equal (=), more (>), less (<), more or equal (≥), less or equal (≤), not equal (≠).

In general, operations can be divided into two kinds:

    action operations;
    relation operations.

Action operations are:

    addition (+)
    subtraction (-)
    multiplication (×)
    division ( ÷ ).

The operations of a relation are:

    equal (=)
    more (>)
    less (<)
    more or equal (≥)
    less or equal (≤)
    not equal (≠)

Documents are **groups of pages** connected through:

- a **sidebar**
- **previous/next navigation**
- **versioning**

## Create your first Doc

Create a markdown file at `docs/hello.md`:

```md title="docs/hello.md"
# Hello

This is my **first Docusaurus document**!
```

A new document is now available at `http://localhost:3000/docs/hello`.

## Configure the Sidebar

Docusaurus automatically **creates a sidebar** from the `docs` folder.

Add metadata to customize the sidebar label and position:

```md title="docs/hello.md" {1-4}
---
sidebar_label: 'Hi!'
sidebar_position: 3
---

# Hello

This is my **first Docusaurus document**!
```

It is also possible to create your sidebar explicitly in `sidebars.js`:

```js title="sidebars.js"
module.exports = {
  tutorialSidebar: [
    {
      type: 'category',
      label: 'Tutorial',
      // highlight-next-line
      items: ['hello'],
    },
  ],
};
```
