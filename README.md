# causal
Causal Inference and The Invariance Principle: An Introduction

by Charles Zheng and Qingyuan Zhao

# Abstract

In this two-part talk, we will give an overview to the field of causal
inference, with the goal of discussing recent developments in the
field such as the Peters et al. "invariant prediction" approach.
We'll introduce Pearl's graphical model approach, popular in
artificial intelligence and structure learning, in contrast with
Rubin's potential outcomes approach, which is more familiar with
statisticians.  While the graphical approach emphasizes discovering
the entire causal structure of the graph, the potential outcomes
approach is more narrowing concerned with estimating a particular
causal effect.  The ``invariant prediction'' approach may provide an
intermediate approach, which learns part of the graphical structure.

# Part I: Introduction

In the first part of the talk, we'll cover the basics of the graphical
approach in causality, and illustrate three main principles: 1. The
causal graph tells you which variables are affected by
intervention; 2. It implies certain conditional independence
relationships; 3. Using simple examples, we illustrate the principle of invariant
prediction, and derivation of both the back-door criterion and
matching approach for estimating an average treatment approach.  Our
focus in this first part of the talk is on core principles and theory:
we leave practical issues and details (including many criticisms and
debates between causal inference researchers, statisticians, and
practitioners) for the second half of the talk, which will be given in
the following week.

# Part II: Invariance

In the second part of the talk, we'll start with the conventional
graphical approach (based on conditional independence tests) and the
conventional functional approach (based on additional distributional
assumptions and MLE), and then introduce the predictive invariance
approach. Our main focus is Section 2--4 of the Peters et al. paper,
but we will also explain why their approach is in some sense "robust"
to model misspecification and hidden variables. The talk is concluded
with an attempt to apply their ICP algorithm to a protein network
dataset.
