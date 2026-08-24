# Application: GTM Engineer I, Blackboard (Anthology)

Posting: Remote, United States. Marketing org, GTM Intelligence & Operations.
Apply at https://jobs.jobvite.com/anthology/job/oIZCAfwD (LinkedIn routes off-platform).
Posted band: $86,900 - $108,600 base. No visa sponsorship.

---

## Cover Letter

Your posting describes an enrichment pipeline that "resolves a contact to the right institution." I have worked the other side of that problem: I did SIS-to-LMS integration at Ellucian, moving student information system data into Blackboard Learn.

In higher ed an institution is not one entity. It is a hierarchy of campuses, colleges, departments, terms, and sections, and integrations break precisely where two systems disagree about which level of that hierarchy a record belongs to. Most B2B enrichment vendors flatten all of it into a single company record. That is why enrichment can look accurate at the vendor level and still route a signal to the wrong buying entity, and why the validation layer matters more than the enrichment itself.

I rebuilt exactly that layer at Accuris, a $500M ARR business where multiple sources disagreed about the same entity and nothing carried provenance. Fixing source precedence and match logic moved match rates from 65% to 89% and cut API waste 40%.

The rest of your responsibilities list is what I have spent the last year doing in-house as a GTM Engineer. I shipped a Slack request-routing app, a BDR lead feed, a competitive intelligence engine, and a PFR auto-logger across Salesforce (SOAP auth), Gong, Neon Postgres, and Linear. On routing, I built territory automation at Go1 covering AUZ, UKI, and US, and a bi-directional Clay and HubSpot pipeline at 1up.ai processing 500+ leads weekly with retry logic and real-time lifecycle updates. On agentic workflows, the orchestration agent I built for Anchor Browser runs on cron and stops at a Slack approval gate before anything reaches a prospect, which is the guardrail I would want around an AI SDR that qualifies before a human touches the lead.

I work in Claude Code daily and build with Python, SQL, and REST APIs against systems that were never designed to talk to each other, which is the whole job in higher-ed integration and most of the job here. I do not hold a Salesforce Administrator certification.

I would welcome the chance to talk about what you are standing up first.

---

## Requirement Map

| Posting requirement | Evidence |
| --- | --- |
| 2+ yrs revenue/marketing ops, GTM systems, growth engineering | In-house GTM Engineer (Cortex) plus consulting: Accuris, 1up.ai, Go1, Ignyte, Anchor Browser |
| Shipped GTM automations/pipelines personally, not directed others | Slack SE request-routing app, BDR lead feed, competitive intel engine, PFR auto-logger, demo preflight |
| Hands-on CRM ownership (Salesforce preferred) | Salesforce integrations incl. SOAP auth; HubSpot deal-stage rebuild, forecast accuracy +30% |
| Integration and API support into CRM | Bi-directional Clay/HubSpot pipeline, 500+ leads weekly, retry logic and review checkpoint before record writes |
| Connecting tools not designed to talk to each other | SIS-to-LMS integration at Ellucian; Salesforce SOAP auth work at Cortex |
| Workflow automation and lead routing | Territory routing automation at Go1 across AUZ, UKI, US regions |
| Signal processing and intent | Signal-based outbound at Cortex; Accuris competitive intel engine monitoring 200+ competitors into HubSpot deal records |
| AI tool deployment and agentic workflows | Anchor Browser orchestration agent, cron scheduling plus Slack approval gate; LangChain/CrewAI |
| Data and contact enrichment, dedupe, normalize, validate | Accuris enrichment and provenance rebuild: 65% to 89% match rates, API waste down 40% |
| Data flows source to CRM to downstream, incl. dedupe and validation | SIS-to-LMS provisioning at Ellucian is this exact shape, with institutional hierarchy as the join key |
| Python or SQL, REST APIs | Yes, plus Neon PostgreSQL in production |
| Fluency with AI coding assistants such as Claude Code | Daily driver |
| **Preferred:** EdTech / higher ed / public sector | **MET.** Ellucian, technical integration work, including integrations into Blackboard Learn |
| **Preferred:** works alongside a separate CRM-owning function | Cortex (RevOps-owned Salesforce); Ellucian integration work crossed system-ownership boundaries by definition |
| Salesforce Administrator certification | NOT HELD. Clay Automated Outbound Certification instead |
| Phave (MAPS), 1mind (AI chat) | No direct experience. Both early-stage; the posting frames them as forward-looking |

---

## Notes Before Applying

**Fill these in before sending.** The letter deliberately says "student information system" rather than naming the product, and gives no dates or scale for the Ellucian work. Swap in the specifics if they help: Banner or Colleague, whether Ethos was involved, roughly how many institutions or integrations, and the years. Naming the product is stronger than the generic phrasing, but only you know which is accurate.

**Why the Ellucian angle is the whole letter.** Two of their preferred qualifications are higher-ed exposure and experience working alongside a separate CRM-owning function. More than that, this is a company hiring someone to resolve contacts to institutions, reading a letter from someone who has moved institutional records into their own product. Very few applicants in a 100-plus pool will have touched Blackboard Learn from the SIS side. Lead with it, which the letter now does in sentence two.

**Leveling.** This is titled Engineer I, banded $86.9K to $108.6K, and describes working "from established patterns and the direction of senior members of the team" in "a career-development role." That is written for someone one to two years in. Your background is past it, and the Ellucian angle widens that gap rather than closing it. Two options: apply as-is and treat the brand plus the AI-native charter as the trade, or raise leveling in the first conversation before investing in interview rounds. Decide before applying, not after an offer.

**Interview questions worth holding.** The team is 25 people and lean by design. RevOps owns Salesforce, marketing does not, so every integration crosses an ownership boundary. The VP of GTM Intelligence & Operations is the direct working relationship. Ask: who arbitrates the Salesforce data model when marketing needs a field RevOps has not approved, and what does the AI SDR do today versus what it is meant to do. A third, which only you can ask credibly: how are they modeling institutional hierarchy in the CRM today, systems versus campuses versus departments, because that decision governs whether the enrichment layer can ever be right.

**Application logistics.** Responses are managed off LinkedIn, so the Jobvite link is the real front door. 100 people had clicked apply on LinkedIn as of the screenshot, one week in.
