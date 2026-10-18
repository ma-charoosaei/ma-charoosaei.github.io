---
title: "On the Risks of using LLM-Generated Tests for Regression Testing"
collection: publications
pubtype: preprints
permalink: /publications/2026-llm-regression-tests-risks/
excerpt: "An empirical study of how LLM-generated regression tests can encode faulty behavior and let bugs persist across software revisions."
date: 2026-10-08
venue: "arXiv preprint arXiv:2610.11835"
paperurl: "https://arxiv.org/abs/2610.11835"
citation: "Charoosaei, M., Richter, C., and Papadakis, M. (2026). On the Risks of using LLM-Generated Tests for Regression Testing. <i>arXiv preprint arXiv:2610.11835</i>."
---

LLM-based test generation can create regression tests directly from the code under test, but when that code is faulty the generated tests may lock in the wrong behavior. Applying LLM-based regression test generation to 145 merged pull requests from SciPy, Qiskit, and pandas, we find that 8%–17% of generated tests are fault-enforcing while only 2.4%–4.8% reveal faults. Fault-enforcing tests persist and accumulate over subsequent commits and largely evade developer-written test suites, so without manual validation, LLM-based regression testing can become a new form of technical debt.

[View preprint](https://arxiv.org/abs/2610.11835) · [PDF](https://arxiv.org/pdf/2610.11835)
