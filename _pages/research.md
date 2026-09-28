---
layout: page
title: research
permalink: /research/
description: Research themes and ongoing work.
nav: true
nav_order: 1
sectioned: true
---

I work at the intersection of **human-computer interaction**, **visualization**, and **software engineering**. My research combines qualitative studies, interactive prototyping, and program analysis to help people understand and improve software and data workflows.

## Visualization and Human Feedback for Data Workflows

_Ph.D. research at Tulane University, advised by [Prof. Rebecca Faust](https://rjfaust.github.io/)_

At Tulane, I study how visualization and interaction can help people reason about data-intensive work, from debugging analysis code to refining the models that underlie text analysis.

### Visual Support for Debugging Data Workflows

Debugging in data-intensive settings (e.g., pandas and computational notebooks) often requires assembling evidence scattered across code, outputs, and intermediate states. Through a qualitative interview study with practitioners, I characterize how people identify discrepancies between expected and observed behavior, and derive visualization design requirements for:

- aligning evidence across scattered artifacts
- comparing expected and observed states
- tracing changes across pipeline stages

This line of work includes a first-author short paper at **IEEE VIS 2026**, a related full manuscript under review at **ACM CHI 2027**, and ongoing prototyping of a visual interface for side-by-side expectation–observation comparison.

### Human Feedback for Text Embedding Refinement

Pretrained embedding models often miss domain-specific semantics. In **KeySI**, we explore how keyword-level human feedback can guide embedding refinement without requiring large labeled datasets or heavy training pipelines. I contributed to study design, pilot sessions, and interface evaluation for this collaborative project (second author, **IEEE VIS 2026** full paper).

## Java Module Encapsulation

_Graduate research at UC Irvine, advised by [Prof. Joshua Garcia](https://jgarcia.ics.uci.edu/)_

At UC Irvine, I studied how Java projects bypass module boundaries to access internal APIs. This work produced an empirical study of Breaking Strong Encapsulation (**ICSE 2026**), the **BEAD** static-analysis tool, and my Master's thesis on automatic detection of encapsulation abuse.

---

A full list is available on the [Publications]({{ '/publications/' | relative_url }}) page.
