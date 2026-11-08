# Role Pack — Product Management (incl. AI / Technical PM)

Load it with the coaching rubric for any PM, Senior PM, Group PM, Technical PM, or AI PM role.

## Frameworks to apply (as tools, not scripts)
- **Behavioural:** STAR or CARL (Context, Action, Result, Learning). Lead with the result or the stakes.
- **Product sense:** clarify → users/segments → pain points → prioritise → solutions → trade-offs → metrics (CIRCLES-style).
- **Execution / metrics:** goal → north-star → input metrics → guardrails, or a metric tree. For a metric drop: clarify → internal vs. external → segment → hypothesise → validate.
- **Prioritisation:** RICE, impact vs. effort, cost of delay. Always name what you're *not* doing and why.
- **Discovery:** JTBD, Mom Test interviews, Opportunity Solution Tree.
- **Strategy:** where to play / how to win, moats, build vs. buy vs. partner, platform vs. point solution.

## AI / Technical PM depth
- **Build vs. buy vs. fine-tune vs. prompt vs. RAG:** decide on speed to validate, data availability, cost, and control.
- **Quality / latency / cost triangle:** name the trade-off explicitly and quantify each side.
- **Evals:** offline (golden sets, LLM-as-judge with human calibration) → shadow mode → canary (e.g. 5% → 20% traffic on thresholds) → online metrics. Layer them: generic model metrics → task metrics → business/domain metrics.
- **Agent design:** tool-calling accuracy, task completion, escalation and human-in-the-loop, risk tiers for actions (read = seamless, write = confirm, destructive = double-confirm).
- **Voice:** WER, latency budget per turn, barge-in, accents and code-switching, MOS.
- **Trust & safety:** hallucination handling, grounding, observability and tracing, failure modes and fallbacks.
- **Sparse-data validation:** historical data as ground truth, proxy metrics, confidence scoring.

## Seed questions (tag in the bank)
**Product sense:** Pick a product you love — what would you remove, and how would you validate it? · Design X for segment Y. · Improve our product for Z.
**Execution:** Conversion dropped 20% after a platform migration with minimal UX change — diagnose. · 60% of new customers fail to go live in 90 days — why, and what do you do? · How would you measure success of feature X?
**Prioritisation:** 12 backlog items, capacity for 5; sales, top customers, user data, and platform scalability all pull different ways — what do you pick?
**AI/Technical:** A customer wants an LLM agent live in 3 months with little training data — approach? · How do you decide when an AI feature is ready to expand traffic? · Walk me through the architecture of something you shipped and the trade-offs.
**Behavioural:** End-to-end product you owned · pushing back on a big customer or your own leadership · a decision under ambiguity · a failure · influencing without authority.
**Strategy / exec:** Where is this market going in 2–3 years? · What's the biggest risk to our strategy? · When do you kill a product?

## Rubric adjustments for PM
- **Case / product sense:** clarifying before solutioning is required for Structure ≥ 8.
- **Execution:** no measurable success criteria → Substance capped at 7.
- **AI/Technical:** no explicit trade-off (quality, latency, cost, risk) → Insight capped at 7.
- **Behavioural:** no explicit personal decision ("I decided") → Substance capped at 7.
