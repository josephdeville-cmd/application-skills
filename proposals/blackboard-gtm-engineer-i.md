# Application: GTM Engineer I, Blackboard (Anthology)

Posting: Remote, United States. Marketing org, GTM Intelligence & Operations.
Apply at https://jobs.jobvite.com/anthology/job/oIZCAfwD (LinkedIn routes off-platform).
Posted band: $86,900 - $108,600 base. No visa sponsorship.

---

## Cover Letter

The hardest line in this posting is "an enrichment pipeline that resolves a contact to the right institution." In higher ed that is not a normal entity-resolution problem. A university is a system, campuses, colleges, and departments, and most enrichment vendors flatten all of it into one company record, so a pipeline that looks accurate at the vendor level quietly routes your signal to the wrong buying entity.

That is the exact layer I rebuilt at Accuris, a $500M ARR business where multiple sources disagreed about the same entity and nothing carried provenance. Fixing source precedence and match logic took match rates from 65% to 89% and cut API waste 40%, and the part that mattered was the validation, not the enrichment.

The rest of your responsibilities list is what I have spent the last year doing in-house as a GTM Engineer: I shipped a Slack request-routing app, a BDR lead feed, a competitive intelligence engine, and a PFR auto-logger across Salesforce (SOAP auth), Gong, Neon Postgres, and Linear. On routing specifically, I built territory automation at Go1 covering AUZ, UKI, and US, and a bi-directional Clay and HubSpot pipeline at 1up.ai processing 500+ leads weekly with retry logic and real-time lifecycle updates. On agentic workflows, the orchestration agent I built for Anchor Browser runs on cron and stops at a Slack approval gate before anything reaches a prospect, which is the pattern I would want around an AI SDR that qualifies before a human touches the lead.

I work in Claude Code daily and build with Python, SQL, and REST APIs against tools that were never designed to talk to each other. I do not hold a Salesforce Administrator certification, and I have not worked in EdTech. What I have is the build history the role asks for.

I would welcome the chance to talk about what you are standing up first.

---

## Requirement Map

| Posting requirement | Evidence |
| --- | --- |
| 2+ yrs revenue/marketing ops, GTM systems, growth engineering | In-house GTM Engineer (Cortex) plus consulting: Accuris, 1up.ai, Go1, Ignyte, Anchor Browser |
| Shipped GTM automations/pipelines personally, not directed others | Slack SE request-routing app, BDR lead feed, competitive intel engine, PFR auto-logger, demo preflight |
| Hands-on CRM ownership (Salesforce preferred) | Salesforce integrations incl. SOAP auth; HubSpot deal-stage rebuild, forecast accuracy +30% |
| Integration and API support into CRM | Bi-directional Clay/HubSpot pipeline, 500+ leads weekly, retry logic and review checkpoint before record writes |
| Workflow automation and lead routing | Territory routing automation at Go1 across AUZ, UKI, US regions |
| Signal processing and intent | Signal-based outbound at Cortex; Accuris competitive intel engine monitoring 200+ competitors into HubSpot deal records |
| AI tool deployment and agentic workflows | Anchor Browser orchestration agent, cron scheduling plus Slack approval gate; LangChain/CrewAI |
| Data and contact enrichment, dedupe, normalize, validate | Accuris enrichment and provenance rebuild: 65% to 89% match rates, API waste down 40% |
| Python or SQL, REST APIs | Yes, plus Neon PostgreSQL in production |
| Fluency with AI coding assistants such as Claude Code | Daily driver |
| Salesforce Administrator certification | NOT HELD. Clay Automated Outbound Certification instead |
| EdTech / higher ed / public sector exposure | NONE (listed as preferred, not required) |
| Phave (MAPS), 1mind (AI chat) | No direct experience. Both are early-stage tools; the posting frames them as forward-looking |

---

## Notes Before Applying

**Leveling.** This is titled Engineer I, banded $86.9K to $108.6K, and describes working "from established patterns and the direction of senior members of the team" in "a career-development role." That is written for someone one to two years in. The build history above is past that. Two options: apply as-is and treat the brand plus the AI-native charter as the trade, or raise leveling in the first conversation before investing in interview rounds. Worth deciding before applying, not after an offer.

**Signals in the posting worth using in an interview.** The team is 25 people and explicitly lean by design. RevOps owns Salesforce, marketing does not, so every integration crosses an ownership boundary. The VP of GTM Intelligence & Operations is the direct working relationship. Good questions: who arbitrates the Salesforce data model when marketing needs a field RevOps has not approved, and what does the AI SDR do today versus what it is meant to do.

**Application logistics.** Responses are managed off LinkedIn, so the Jobvite link is the real front door. 100 people had clicked apply on LinkedIn as of the screenshot, one week in.
