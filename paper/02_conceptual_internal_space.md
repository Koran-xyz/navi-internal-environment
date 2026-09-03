# 2. Conceptual Internal Space (CIS)

## 2.1 Operational Definition

**Conceptual Internal Space (CIS)** is a conceptually defined contextual space constructed through natural-language boundary declarations, within which rules, states, roles, or structures can be organized and applied in a functionally distinguishable manner, without requiring a separately implemented software environment or implying the existence of a distinct physical or neural space within the model.

In this paper, the term *internal* refers to the functional distinction established within the conversational context rather than to a claim about the physical or neural organization of the underlying model. A CIS is therefore identified through observable behavior associated with a conceptually defined boundary: the model distinguishes contexts, applies context-dependent rules or states, and changes the applicable behavior when the declared boundary changes.

The purpose of the CIS concept is not to assert a hidden implementation mechanism. It is an operational description intended to make the observed behavior testable across different LLM platforms.

## 2.2 Minimum Criteria

For the purposes of this study, a candidate interaction is treated as exhibiting CIS-like behavior when the following minimum criteria are observed:

1. **Natural-language boundary definition.** A distinguishable region or context is declared using natural language, such as an INSIDE/OUTSIDE distinction.
2. **Functional differentiation.** Different rules, states, roles, or structures can be associated with the defined regions or contexts.
3. **Boundary-dependent switching.** When the declared context changes, the model can switch to the rule or state associated with the newly active region.
4. **Contextual persistence.** The distinction can remain functionally observable beyond a single isolated response, allowing its behavior to be examined across multiple turns.

These criteria do not establish that a separate internal mechanism exists. They provide an operational threshold for deciding whether behavior corresponding to a conceptually defined space is present and therefore suitable for further testing.

## 2.3 What CIS Does Not Claim

CIS should not be interpreted as:

- a separately instantiated software environment;
- evidence of a physically distinct region inside an LLM;
- evidence of a distinct neural subsystem;
- proof that different LLM platforms implement the same internal mechanism; or
- proof that natural-language rules are universally portable across all models.

The present claim is deliberately narrower: **functionally observable behavior corresponding to a conceptually defined space can be studied without assuming the physical existence or implementation mechanism of that space.**

This distinction is essential for cross-platform comparison. Different LLM platforms may represent or process the same natural-language boundary in different ways while still producing comparable functional outcomes. The question of whether such outcomes converge across platforms is treated as an empirical question rather than an assumption.

---

## Open Research Note

This section provides an operational working definition rather than a claim about the hidden physical or neural implementation of large language models. The definition may be refined as further cross-platform experiments, negative results, and independent replications are added.

**Next:** Natural-Language Rule Construction — how boundaries and rules are introduced, modified, and evaluated without requiring platform-specific software implementation.
