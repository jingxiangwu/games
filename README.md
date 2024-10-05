# Games
Games theory, Strategies, Monte Carlo and Nash equilibrium


## Three-way duel

Alice, Bob, and Carol arrange a three-way duel. Each of the three has a gun and plenty of ammunition.

If anyone takes a shot at one of his opponents, there is a fixed probability of killing whomever he shoots at. The probabilities are $p_A$, $p_B$ and $p_C$ and we assume $p_A \leq p_B \leq p_C$.

They take turns shooting, first Alice, then Bob, the Carol, then back to Alice, and so on until one is left. What is Alice's best course of action? We assume that all players act rationally. They will maximize their chance of survival.

**Remark**: Most of the solution I found online simply focus solely on the First Shot advantage, and conclude **wrongly** that Alice should simply shoot into the air. We will demonstrate this is only true in certain circumstances and in general, one needs to compare quantitatively two strategies.

We will compute the probability of survival analytically and then check explicitly using a <ins>simulator</ins>!



## Two-player stopping game

Two players are playing a game where they each draw a secret random number uniformly between 0 and 1. If they are not satisfied with their draw they may redraw.

The players do not know whether or not the other has chosen to re-draw. The players then compare their numbers and he/she who holds largest number wins.

**Remark**: the answer is not to set a threshold at 0.5, as one might naively think.
