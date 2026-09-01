# Conceptual Internal Spaces in Large Language Models

## A Cross-Platform Hypothesis from Natural-Language Rule Construction

**Status:** Working Paper — Version 0.1  
**Research stage:** Exploratory / hypothesis-forming  
**Last updated:** 2026-09-01

> This is an open research process. This document is not presented as a finished answer. Chapters, experiments, unexpected results, failures, and revisions will be added as the research develops. Independent replication, criticism, falsification, and extension are welcome.

# 1. Introduction

Large language models (LLMs) are increasingly deployed across different platforms, each with its own model architecture, system design, instruction hierarchy, and operational constraints. Despite these differences, natural language remains the primary interface through which users define tasks, roles, constraints, and expected behavior.

This raises a fundamental question: **Can rules constructed solely through natural language function across different LLM platforms?**

If natural-language-defined rules can be recognized and followed across independently implemented AI platforms, natural language may serve not only as a communication interface but also as a potential **platform-independent rule layer**. Such a capability could provide a lightweight method for defining behavioral structures without requiring direct modification of model parameters or platform-specific software implementations.

In exploratory interactions with multiple LLM platforms, we observed that natural-language-defined rules could produce functionally similar rule-following behavior despite differences in platform-specific responses. The platforms did not necessarily respond identically. In some cases, particularly as rule structures became more complex, distinct platform-dependent behaviors and apparent boundary effects were observed. Nevertheless, basic functions such as rule recognition, contextual separation, and rule-following appeared across multiple environments.

To describe these observations, we introduce the working concept of a **Conceptual Internal Space (CIS)**. CIS does not refer to a physically implemented software environment or claim the existence of a distinct neural space within an LLM. Rather, it describes a conceptual structure defined through natural language in which rules, boundaries, states, or roles can be organized and can influence subsequent model behavior.

The primary research questions of this work are therefore:

> **RQ1:** Can rules constructed solely through natural language function consistently across different LLM platforms?
>
> **RQ2:** If platform-specific responses differ while fundamental rule-following functions remain similar, does this suggest the possibility of a platform-independent natural-language rule layer?

This paper presents these questions as part of an exploratory and open research program. Rather than claiming definitive evidence of a universal internal mechanism, we report preliminary observations, define the proposed conceptual framework, identify platform-specific differences, and formulate hypotheses that can be independently tested, challenged, and extended.

---

## Open Research Note

This chapter is the first public working section of the paper. Future updates will add the definition of Conceptual Internal Space, experimental records, cross-platform observations, negative results, hypotheses, limitations, and reproducibility materials. The purpose of this repository is to expose the research process as it develops, rather than waiting until every question has been resolved.