
# Missionaries and Cannibals Problem

Solutions for the [Missionaries and Cannibals Problem](https://en.wikipedia.org/wiki/Missionaries_and_cannibals_problem).

> In this problem, three missionaries and three cannibals must cross a river using a boat which can carry at most two people, under the constraint that, for both banks, if there are missionaries present on the bank, they cannot be outnumbered by cannibals (if they were, the cannibals would eat the missionaries). The boat cannot cross the river by itself with no people on board. And, in some variations, one of the cannibals has only one arm and cannot row. [source: Wikipedia]

## Solutions

First was defined the 10 rules that determine which are the possible successor states for each possible action. Then a recursive rule `path` is responsible for find the solution of the problem.

Running the Prolog code in [SWI-Prolog](http://www.swi-prolog.org/):

```
?- ['missionaries_and_cannibals.pl'].
?- find.
```

