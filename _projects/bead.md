---
layout: page
title: BEAD
description: Static analysis for detecting Breaking Strong Encapsulation in Java modules.
img: assets/img/publication_preview/chen2024thesis.png
importance: 3
topics: [Static Analysis, Java, JPMS]
category: research
github: https://github.com/CyberSakura/BEAD
---

BEAD (Breaking Encapsulation Abuse Detector) is a static-analysis tool that detects access to JDK-internal APIs through direct calls and reflection. It uses JavaParser, Soot, call graphs, and dataflow analysis to report encapsulation violations under the Java Platform Module System (JPMS).

This work grew out of an empirical study of Java module abuse and my Master's thesis at UC Irvine.

**Outcomes**
- ICSE 2026 co-authored paper on Breaking Strong Encapsulation
- Master's thesis: *Automatic Detection of Breaking Strong Encapsulation in Java Modules* (2024)
- [Thesis PDF](https://escholarship.org/uc/item/2tf1d64x)
- [GitHub](https://github.com/CyberSakura/BEAD)

Advisor: [Prof. Joshua Garcia](https://jgarcia.ics.uci.edu/)
