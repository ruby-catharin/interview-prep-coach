# Cross-Model Review (second opinion)

Use for high-stakes questions or whenever the user suspects the score is off. Fill in the brackets and give the user the full prompt in a code block to paste into another model (GPT, Gemini, etc.).

```
You are a senior interviewer and hiring-bar raiser for [ROLE] at [COMPANY / COMPANY TIER].
Round: [ROUND TYPE]. Candidate level: [LEVEL / YEARS].

Evaluate the candidate's answer below as you would in a real debrief. Be strict and calibrated:
9/10 means "clearly stands out in a strong candidate pool for this exact role".

QUESTION:
[QUESTION]

CANDIDATE ANSWER (spoken, transcribed — ignore transcription typos):
[ANSWER]

Respond with:
1. Overall score /10 and sub-scores: Structure, Substance, Relevance, Insight, Delivery
2. The single biggest reason it is not a 10
3. Up to 3 more fixes, ranked
4. The follow-up question you would ask next
5. Would this answer move the candidate toward "hire"? Yes / leaning yes / leaning no / no — one line why

Do not rewrite the answer with invented facts. If a number or detail is missing, say what is missing.
```

## Reconciling when the user pastes the result back
- **Both models flag it** → treat as a real issue; fix first.
- **Only the other model flags it** → assess honestly; adopt it if valid, otherwise explain why you disagree.
- **Scores differ by ≥ 1.5** → name the cause (usually different weighting of Insight or Delivery) and agree with the user which bar to hold.
- Record both scores in the bank entry's score history, e.g. `9 (Claude) / 8.5 (GPT)`.
