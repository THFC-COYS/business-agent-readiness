# Business Agent Readiness

**Your customers are already messaging you. This toolkit tells you whether an AI agent should be answering, and exactly what to fix first.**

Business Agent Readiness is an open assessment and planning toolkit for businesses adopting AI business agents: Meta Business Agent on WhatsApp, and Muse-powered agents on the channels customers already use. Answer 15 questions, get a readiness score across five dimensions, a maturity stage, and a prioritized adoption plan with governance checks, a channel plan, and starter agent blueprints.

Built by Greg Lucas, a Muse early adopter and advocate. Design law for this project, and for every project in this portfolio: agents first, Muse first. The agent is the default worker; the human is the accountable owner.

Companion projects: [Muse Exchange](https://muse-exchange.vercel.app) (the marketplace for Muse agents), [MuSe SIM](https://muse-sim.vercel.app) (a society of Muse agents), and [agentlint](https://github.com/THFC-COYS/agentlint) (the governance linter for AI agents).

## Run the assessment

No build step, no dependencies, no server. One file:

1. Open `index.html` in any modern browser (double-click it, or serve the folder with any static host or GitHub Pages).
2. Answer the 15 questions honestly for where your business is today.
3. Get your report on screen, then copy it as text to share with your team.

## The five readiness dimensions

The assessment operationalizes the **AGENT Framework** by Greg Lucas. Each dimension is scored 0 to 100 from three questions answered on a five-point scale.

| Dimension | What it measures |
| --- | --- |
| **Acumen** | You know where agents create value: the top customer conversations to hand over first, the questions customers actually ask, and a team that understands the agent's scope. |
| **Governance** | Every agent has a named human owner and a census entry. Sensitive actions sit behind approval gates. A tested kill switch and a human handoff path exist before launch, not after an incident. |
| **Evaluation** | Agent work is measured like staff work: scheduled conversation reviews, resolution and escalation rates, and a feedback loop that fixes the knowledge base within days. |
| **Navigation** | The rollout is planned and the channels are ready: WhatsApp Business and Meta Business settings prepared, one channel first, a pilot group, and clear go or no-go criteria. |
| **Transformation** | Workflows are redesigned around agents instead of decorated with them, agent results appear on the business scorecard, and a second workflow is already on the roadmap. |

## Maturity stages

Your overall score places you on a four-stage maturity path:

- **Stage 1, Explore (0 to 24):** one safe, narrow agent on one channel, a human watching closely.
- **Stage 2, Pilot (25 to 49):** a real pilot on WhatsApp with a small customer group, measured, with gaps fixed as they surface.
- **Stage 3, Deploy (50 to 74):** agents in front of most customers on your main channels, governance and measurement running as routine.
- **Stage 4, Transform (75 to 100):** agents are part of how the business runs. Scale them: more workflows, proactive agents, cloned blueprints.

## What the plan gives you

- **Do first:** concrete moves for your three weakest dimensions, in priority order.
- **Governance checks:** the status of your agent census, approval gates, and kill switch, plus the data rules, escalation path, and review cadence to verify before launch.
- **Channel plan:** a phased rollout that starts on WhatsApp with Meta Business Agent, adds a Muse-powered web agent on the same knowledge base, then extends to booking, proactive follow-up, and cloned blueprints as your stage allows.
- **Agent blueprints:** starter templates matched to your stage, from the Front Door Agent (FAQ and routing) to the Booking and Intake Agent, the Follow-Up Agent, and an internal Operations Copilot. Every blueprint follows the pattern proven on Muse Exchange: scoped tools, approval gates, logging, and a named owner.

## Example output

For a sample business (a multi-location services company, invented for this example) that answers honestly and lands mid-pack:

```text
BUSINESS AGENT READINESS REPORT
Overall score: 45/100
Maturity stage: Stage 2: Pilot

Dimension scores:
- Acumen: 67/100
- Governance: 25/100
- Evaluation: 42/100
- Navigation: 58/100
- Transformation: 33/100

Do first:
- Governance: Create your agent census today: one page listing every planned
  agent, its owner by name, its channels, and what it is allowed to do.
- Governance: Set the two non-negotiables before launch: approval gates on
  refunds, discounts, and commitments, and a kill switch with a named human
  who can pull it.
- Transformation: Choose one workflow to redesign end to end around the agent
  (booking, intake, ordering, or support) instead of adding a chat box to the
  old process.
...

Governance checks:
- [Partial] Named human owner and written agent census
- [Partial] Approval gates on refunds, discounts, commitments, and sensitive data
- [Missing] Kill switch and human handoff path, tested by staff
...

Channel plan:
- Phase 1, WhatsApp first: connect Meta Business Agent to the WhatsApp number
  your customers already message. Load it with approved FAQ knowledge only,
  and keep a human one tap away.
- Phase 1, web: add a Muse-powered agent to your website using the same
  approved knowledge base, so answers stay consistent across channels.
```

The pattern is the point: the score is not a grade, it is a work order. Governance at 25 means the plan leads with the census, the approval gates, and the kill switch before any channel scales.

## Why Muse-first

Meta is putting agents where business conversations already happen: inside WhatsApp and Messenger, through Meta Business Agent, and on the open web through Muse. A business that plans around that reality, with governance in place before scale, adopts faster and safer than one that starts with a generic chatbot project. This toolkit is the planning layer for that adoption, written by someone who builds on Muse in public every day.

## Author

**Greg Lucas** is the Founder of pAIgeBreaker (personalized AI textbooks and Aithentik authorship verification) and AIccountable (safe, governed AI adoption for companies). He created the AGENT Framework (Acumen, Governance, Evaluation, Navigation, Transformation) and the 4-Stage AI Maturity Model, built Muse Exchange and MuSe SIM on Meta Muse, and writes and speaks on agentic AI in business and education.

- Muse Exchange: https://muse-exchange.vercel.app
- MuSe SIM: https://muse-sim.vercel.app
- pAIgeBreaker: https://paigebreaker.com
- LinkedIn: https://www.linkedin.com/in/greg-lucas-28765b416/

## License

MIT. Copyright (c) 2026 Greg Lucas. See [LICENSE](LICENSE).
