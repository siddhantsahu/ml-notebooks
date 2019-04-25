This repository is a collection of several problems in ML/AI/NLP (mostly) I work on from time to time.
Inspiration: this amazing [repository](https://github.com/norvig/pytudes) by Peter Norvig.

### Problems
1. **Phrase learning in PySpark:** A very common use case for text mining and NLP problems.
This implementation is suitable for finding phrases in large datasets.
2. **Search methods in AI:** Comparision of breadth first search, iterative deepening search and
A-star search for solving the 8-puzzle problem.
3. **Constraint satisfaction problem in AI:** Uses the N-Queens puzzle to demonstrate two algorithms - minimum conflicts
and heuristic-augmented backtracking.

Here is a list of other interesting problems that I may work on in the future.
1. Route planning for public transit network.
2. Topic based pagerank (an extension of the pagerank algorithm)
3. A Cython implementation for the spell correction algorithm, [Symspell](https://github.com/wolfgarbe/SymSpell). Ports in
Java, Python and C++ exist but integrating C++ and Java modules in data pipelines (which are usually Python based) is a
hassle. A Cython module can bridge the gap and still be as fast as the C++ or Java module.
