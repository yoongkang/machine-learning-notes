# Introduction {#chapter-intro}

This chapter introduces some different kinds of machine learning at a very high level.

The motivation for these kinds of machine learning algorithms is described, with a short description of what happens in layman's terms.

## Supervised learning

### Decision trees

A decision tree is basically a tree that looks at a data point and asks yes/no questions until it arrives at a leaf (decision).

For example, say we want to know if a person owns a car. That is, the set of classifications is "Own car" and "Doesn't own car". We ask questions like "is this person over 16", "is this person's household income over $X", etc.

Each question (or node) divides the data into sections until we reach an outcome.

The training algorithm will be described in [chapter 3](#chapter-supervised-learning), but essentially each question aims to minimize a cost function called "entropy".

