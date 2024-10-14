# Chapter 1 - Introduction (It's all about complexity)

Ousterhout claims that "Complexity increases inevitably over the life of any program" (p. 1) and that in order to protect productivity, simpler designs must be implemented so that the complexity doesn't grow so much as to overwhelm developers contribuiting to the project.

---

Two paths to reducing complexity are highlighted in this book:

- Eliminating complexity by making code simpler (ex. eliminate special cases, using consistent naming)
- Encapsulate comlexity so that developers can work on smaller components of a system without being exposed to all the complexity of the entire system.

---

Unlike the design of physical mediums like buildings or bridges, the design of software is a continuous process throughout the life of the project. This is due to software's flexibility. Large portions of a system can be redesigned, and indeed often need to be to meet new requirements. This is in contrast with say, a building because at some point, the building will be "done" and the design process complete.

"[Software's] initial design will have many problems" (p. 2) because it is impossible to understand all the implications of decisions before building anything.

---

The goal of this book is to:

1. Shed a light on complexity, what it means, and how to recognize it.
2. Tactics on dealing with complexity.

---

Throughout the book, we'll be highlighting _red flags_ that are indicators of poor design. Ousterhout says the easiest way to start using this book is to look for these red flags in code reviews.

---

Any principle can be taken to the extreme, and doing so will often not end up in the best result. With any guiding principle, there is nuance.
