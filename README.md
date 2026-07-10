# Imperative vs Declarative Programming
In Chapter 3, I practiced updating the UI using imperative JavaScript, which means telling the browser exactly how to perform each step. Imperative code focuses on how to do something. For example, creating an element, creating a text node, attaching it, and inserting it into the DOM.

React, however, uses a declarative approach. Declarative code focuses on what you want to show, and the library handles the steps required to update the DOM. Instead of manually manipulating elements, you simply describe the UI, and React takes care of rendering and updating it efficiently.

As applications grow, the declarative style becomes easier to maintain, easier to read, and reduces the amount of low‑level DOM code developers need to write.

## Pizza Example

### Imperative Programming
Imperative programming is like giving the chef step‑by‑step instructions to make a Hawaiian pizza. You explain how to do every part of the process:

- Knead the dough
- Stretch it into a circle
- Spread tomato sauce
- Add mozzarella cheese
- Place slices of ham
- Add pineapple
- Bake at 200°C for 15 minutes

You are describing each action required to reach the final result.
This is similar to manually updating the DOM in JavaScript.

### Declarative Programming
Declarative programming is like simply telling the chef:

“I want a Hawaiian pizza.”

You describe what you want, not how to make it.
The chef decides the steps, the order, and the details.

This is how React works: you describe the UI you want, and React figures out the DOM updates internally.