# Learnings Log

This repository is a living record of how I explore AI system behavior
through prompt design, structure, and iteration.

The goal is not polished demos, but rapid understanding.

---

## Learning 1: Prompt Framing Changes Cognitive Behavior

**Observation**
When the assistant is framed as a “coach” instead of an “answer engine”,
its responses become more exploratory and adaptive.

**Hypothesis**
Explicit role constraints influence reasoning depth and interaction quality.

**Next Step**
Test variations:
- Coach with strict refusal to answer
- Coach with delayed answer reveal
- Coach that mirrors user reasoning

---

## Meta Reflection

I am optimizing for learning velocity rather than surface performance.
I expect some experiments to fail.
Those failures are signals, not waste.


---

## Learning 2: Role Framing Changes Collaboration Style

**Observation**  
When the assistant is framed as a peer reasoner rather than a coach,
responses become more exploratory and transparent, but less directive.

**Comparison**
- **Coach:** Structured, guiding, pedagogical
- **Peer:** Collaborative, uncertain, hypothesis-driven

**Tradeoff**
- Coach framing improves clarity and progression.
- Peer framing improves openness and joint reasoning.

**Implication**
Different role framings may be optimal for different user goals.
A hybrid or adaptive role could outperform both.

**Next Step**
Design a prompt that dynamically shifts between peer and coach roles
based on user signals.

