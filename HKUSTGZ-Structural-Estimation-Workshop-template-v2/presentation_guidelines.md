# Presentation Guidelines

For application and replication sessions, the goal is to explain **how structural estimation is actually implemented**.

## Suggested Presentation Structure

1. **Model and economic mechanism** — no more than 30 minutes
2. **Data, estimation, and implementation** — 45 to 60 minutes
3. **Replication results and discrepancies** — 15 to 20 minutes
4. **Discussion** — at least 15 minutes

## The Implementation Section Should Answer

- What are the estimated parameters?
- What moments, likelihood objects, or equations identify them?
- How is the model solved?
- How is the estimator computed?
- What numerical problems appeared?
- Which results were replicated successfully?
- Where do the results differ from the paper, and why?

## Replication Expectations

You do **not** need to reproduce an entire paper.

A good replication can focus on one:

- key table,
- figure,
- set of moments,
- parameter estimate,
- or counterfactual.

The important part is that the implementation is clear and reproducible.

Replication packages may be used as guidance, but participants are encouraged to rewrite and reorganize code in their own style and to read appendices and documentation carefully.
