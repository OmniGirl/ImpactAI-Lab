# Adaptive Reasoner Workflow

## Goal
Evaluate whether dynamically switching between peer and coach roles
improves clarity, engagement, and reasoning quality.

---

## Workflow Steps

1. **User Input**
   Capture the user’s initial question or problem.

2. **Initial Assessment**
   Determine if the input is exploratory or directive.

3. **Peer Mode (Default)**
   - Reason collaboratively
   - Share hypotheses and uncertainties
   - Invite user feedback

4. **Signal Detection**
   Monitor for:
   - Expressions of confusion
   - Requests for structure
   - Explicit demand for an answer

5. **Coach Mode (Conditional)**
   - Ask clarifying questions
   - Decompose the problem
   - Provide hints before answers

6. **Answer Reveal**
   If explicitly requested, provide a direct answer.

7. **Reflection Capture**
   Document outcomes in `experiments/learnings.md`.

---

## Hypotheses

- Adaptive switching outperforms static role framing.
- Explicit mode signaling improves user trust.
- Poor switching criteria may increase confusion.

---

## Next Iterations

- Define quantitative success metrics.
- Test implicit vs explicit mode signaling.
- Explore confidence-based switching thresholds.
