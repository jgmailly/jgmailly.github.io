---
layout: page
title: Pygarg
description: A Python enGine for Argumentation
img: assets/img/pygarg_logo.png
importance: 1
category: software
related_publications: halPygarg2024, argAndComp2024b
---

[pygarg](https://github.com/jgmailly/pygarg) is a Python implementation of SAT-based techniques for abstract
argumentation. It is based on CoQuiAAS, with all calls to SAT solvers
using the [pysat](https://pysathq.github.io/installation/) API.

Based on the command-line interface of the ICCMA competitions, it can
solve the problems XX-YY with:
- XX in ['DC', 'DS', 'SE', 'EE', 'CE'] standing for credulous
  acceptability, skeptical acceptability, computing some extension,
  enumerating extensions and counting extensions;
- and YY in ['CF', 'AD', 'ST', 'CO', 'PR', 'GR', 'ID', 'SST'] standing
  for conflict-freeness, admissibility, stable semantics, complete
  semantics, preferred semantics, grounded semantics and semi-stable semantics.

pygarg can be installed thanks to the Python Package Index:
```bash
pip install pygarg
```

See {% cite argAndComp2024b %} or the [GitHub](https://github.com/jgmailly/pygarg) repository for more details on how to use pygarg, via the command-line or as a library in your own Python script.
