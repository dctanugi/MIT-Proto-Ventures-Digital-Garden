---
tags:
  - needs
  - work/proto_ventures
  - work/industries/grid
---
## Description of need
The ACOPF is at the heart of Independent System Operator (ISO) power markets, and is solved in some form every year for system planning, every day for day-ahead markets, every hour, and even every 5 minutes ([source](https://www.ferc.gov/sites/default/files/2020-05/acopf-1-history-formulation-testing.pdf)).

Real-world SC-ACOPF problems may involve power grids with more than 30,000 buses and 22,000 contingencies and need to be solved within 10–45 minutes to get a base case solution with high feasibility and reasonably good generation cost. 

This is still an open area:
>50 years after the problem was formulated, we still do not have a fast, robust solution technique for the full ACOPF. Finding a good solution technique for the full ACOPF could potentially save tens of billions of dollars annually

## Problem severity (1-10)
8

## Who has this need
- ISOs for:
	- Security-Constrained Economic Dispatch

## Total addressable market (TAM)
- Tens of billions of dollars according to one source


## Solutions today, and their shortcomings


## Potentially relevant capabilities
- [[Andy Sun]] and [[Thomas Lee]] at MIT: [[ADMM-based Distributed Optimization Method for Solving Security Constrained AC Optimal Power Flow]]
- [[Priya Donti]] at MIT
- [[Audun Botterud]] at MIT
- https://ieeexplore.ieee.org/document/9303008/authors#authors by Kyri Baker at U Colorado
- https://www.sciencedirect.com/science/article/pii/S0378779622005636

## References
see [[2024-05-20 Thomas Lee]]

## Research notes
- [[Kyri Baker]] at U. Colorado has done extensive research in this field and appears to be involved with [[Yes Energy]] (see [blog post](https://blog.yesenergy.com/yeblog/using-ai-and-machine-learning-for-power-grid-optimization)). In this blog post, she describes how we could improve the Security-Constrained Economic Dispatch (SCED) process by replacing the DC OPF step with a neural network emulator of an AC OPF optimizer. The ISO would still run a traditional AC OPF algorithm ex post facto, like today, presumably because we can't trust the black box of a machine learning model. The intended benefit would be faster solutions and more optimal solutions relative to today's DC OPF algorithms.
- Relevant paper by [[Kyri Baker]]: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10252655
- Savings from improvements in optimization techniques are in the $100M/yr range for each ISO ([source](https://www.ferc.gov/sites/default/files/2020-05/rto-iso-soft-2011.pdf))
- Each ISO uses a slightly different approach for economic dispatch ([source](https://www.ferc.gov/sites/default/files/2020-05/rto-iso-soft-2011.pdf))
- Relevant article on ARPA-E AC OPF competition: https://arxiv.org/pdf/2206.07843