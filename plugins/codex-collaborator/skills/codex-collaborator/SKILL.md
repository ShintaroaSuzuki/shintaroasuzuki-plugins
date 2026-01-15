---
name: codex-collaborator
description: Collaborate with Codex CLI through iterative AI-to-AI discussion. Use whenever the user mentions "Codex" in any context—asking for Codex's opinion, consulting Codex, discussing with Codex, or any request involving Codex collaboration. Also triggers on phrases like "ask another AI", "get a second opinion from AI", or "AI-to-AI discussion".
---

# Codex Collaborator

Collaborate with Codex CLI for objective, multi-perspective analysis.

## Core Principles

### Objective Dialogue

Request Codex to provide **unbiased, objective analysis**:

-   Ask for honest critique, not validation
-   Request counterarguments and potential flaws
-   Value disagreement as a path to better decisions

### Iterative Refinement

Continue discussion until convergence—no fixed number of rounds.

## Workflow

### 1. Frame the Question

Include:

-   Context and constraints
-   Specific decision point
-   **Request for objectivity**: "Be critical. Point out flaws. Don't defer to any assumed preference."

### 2. Execute Codex

```bash
codex exec "YOUR_PROMPT" --sandbox read-only
```

### 3. Analyze & Iterate

After each response:

-   Identify disagreements and new perspectives
-   Formulate follow-up questions if needed
-   Continue until a clear synthesis emerges

### 4. Synthesize

Combine insights:

-   Areas of consensus
-   Unresolved disagreements
-   Final recommendation with rationale

## Prompt Template

```
[TOPIC/QUESTION]

Context: [CONTEXT]

Important: Provide objective analysis. Be critical and point out flaws.
Don't defer to any assumed preference. If you disagree, say so clearly.
```

## Best Practices

-   Explicitly request objectivity in every prompt
-   Challenge responses with counterarguments
-   Probe for hidden issues
-   Value uncertainty over false confidence
