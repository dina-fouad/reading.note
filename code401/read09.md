## What Are Dunder Methods?
In Python, special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores, for example __init__ or __str__.

 Dunder methods let you emulate the behavior of built-in types. For example, to get the length of a string you can call len('string').

## Special Methods and the Python Data Model
This elegant design is known as the Python data model and lets developers tap into rich language features like sequences, iteration, operator overloading, attribute access, etc.

- Object Initialization: __init__
- Object Representation: __str__, __repr__
- Iteration: __len__, __getitem__, __reversed__
- Operator Overloading for Comparing Accounts: __eq__, __lt__
- Operator Overloading for Merging Accounts: __add__
-  Callable Python Objects: __call__


## Basic Statistics in Python — Probability

We started with descriptive statistics and then connected them to probability. From probability, we developed a way to quantatively show if two groups come from the same distribution. In this case, we compared two wine recommendations and found that they most likely do not come from the same score distribution. In other words, one wine type is most likely better than the other one. Statistics doesn’t have to be a field relegated to just statisticians. As a data scientist, having an intuitive understanding on common statistical measures represent will give you an edge on developing your own theories and the ability to subsequently test these theories. We barely scratched the surface of inferential statistics here, but the same general ideas here will help guide your intuition in your statistical journey