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

## Relation operations

Let's start with attitude operations. The word "relation" speaks for itself. Examples from life: something has to do with something. Dad has a relation to mom. This relation is called a marriage.

Examples of relationships abound. We can say that our beautiful world, which develops harmoniously, also consists of relationships.

If a five is greater than a three, we say that "a five is greater in relation to a three" and write it down as 5 > 3 (read: five is greater than three). The acute angle of the sign of the ratio must point in the direction of the smaller number. In this example, the number 3 is smaller than the number 5, so the acute angle of the sign of the ratio is directed toward the number 3.

Another example. The number 11 is less than the number 15. This phrase can be written as follows:

`11 < 15`

In mathematics, you can use relations to write laws, formulas, equations, and functions. It can be written that one expression is equal to another, or some action is unacceptable in relation to some object, number, law.

For example, the famous phrase "you cannot divide by zero" is written like this:

_You can't divide by zero._

Let's not get ahead of ourselves. Let's just say that this expression can contain any numbers instead of a and b. But then it is said that b must not be equal to zero.

The equal sign = is put between the quantities and says that the quantities are equal to each other.

For example, "five equals five" is written as `5 = 5`. It is clear that two fives are equal to each other. In addition to prime numbers, the equal sign can connect more complex expressions, for example: `9 + x + y = 4 + 5 + x + y`.

Another example: If one large watermelon weighs 20 kg and two small watermelons weigh 10 kg each, then between a watermelon of 20 kg and two watermelons of 10 kg we can put an equal sign. This relation can be read as "one watermelon weighing 20 kilograms equals the weight of two watermelons each weighing 10 kilograms". After all, `20 kg = 10 kg + 10 kg`.

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
