---
title: "Deep RL 2 Imitation Learning"
date: 2021-03-14
categories:
  - DeepRL
tags:
  - RL
  - notes
usemathjax: true
---
The framework of imitation learning tackles reinforcement learning as a supervised learning problem.

## Some Basic Notations
\[o_t\]: observation at time $t$

$s_t$: state at time $t$

$a_t$: action at time $t$

$\pi_{\theta}(a_t|o_t)$: policy, a distribution over actions $a_t$ given observation $o_t$, sometimes also use $\pi_{\theta}(a_t|s_t)$.

