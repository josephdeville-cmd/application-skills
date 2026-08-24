# Upwork Proposal: Land Brokerage Claude Skills Consultant

Posting: Texas rural land / timberland brokerage seeking advanced Claude consultant
to identify, build, test, and refine Skills and workflows across 8-10 live hours.

---

## Cover Letter

Every Skill on your list (CMA, MLS copy, listing audit, buyer match) depends on the same object: a verified property record. Build that first and the rest become thin wrappers. Skip it and you end up with eleven Skills that each re-derive acreage from a different source and quietly drift apart.

That is also where your accuracy requirement actually gets solved. Claude does not invent acreage at random, it invents when a field is blank and the surrounding template demands prose. So the fix is structural, not a prompt that says "do not hallucinate." I would build the property record with a per-field source URL, a confirmed / unconfirmed / conflicting state, and a hard rule that downstream Skills render an explicit gap ("survey acreage not verified, deed says 47.3, MLS says 48") instead of writing around it. Once that exists, your CMA Skill, long-form description, Land.com copy, and brochure all read from one record, and correcting a fact once corrects it everywhere.

The closest work I have done to this is rebuilding enrichment logic at Accuris, a $500M ARR business, where the real problem was the same one you have: multiple sources disagreeing about the same entity with no provenance layer. Fixing source precedence and match logic moved match rates from 65% to 89% and cut API waste 40%. On the approval side, the orchestration agent I built for Anchor Browser runs on a schedule but stops at a Slack checkpoint before anything reaches a person, which is the pattern I would use for anything client-facing in your brokerage.

I want to be straight with you on one requirement: my hands-on Claude and automation work has been in B2B revenue operations, not inside a brokerage. I know property data, comps methodology, and MLS workflows as a systems problem, not from carrying a license. If direct brokerage experience is non-negotiable, I would rather you know that in sentence one than in hour three of a paid session.

What I would realistically finish in 8-10 hours: an audit of your current Skills and connectors with a written kill / keep / merge list, the verified property record and the CMA Skill built and regression-tested against two closings where you already know the right answer, the marketing copy suite reading from that record, and a Skill that writes new Skills in your house format so you are not dependent on me afterward. I will send a short video walking through one of these builds so you can judge the communication before you commit a day to it.

---

## Screening Answers

**1. Hands-on Claude experience**

I build production systems on Claude, not chat workflows. Most recent: a year in-house as a GTM Engineer shipping a Slack request-routing app, a BDR lead feed, a competitive intelligence engine, and an auto-logger, spanning Salesforce (SOAP auth), Gong, Neon Postgres, and Linear. I work daily in Claude Code, Projects, and Skills, and I have built and debugged MCP connectors, so when a connector silently returns partial data I know where to look. I also write Skills with the failure mode in front: what should this refuse to do, and what does it do when the input is incomplete.

**2. Direct real estate experience**

Stated plainly above: my Claude work has been in B2B revenue operations, not inside a brokerage. What transfers is the exact problem class you described, entity records assembled from conflicting sources where a wrong field costs money. At Accuris I rebuilt that layer for company data; at Ignyte I built lead qualification under CMMC and FedRAMP constraints, where unsupported claims are a compliance event, not a typo. If you want someone who has personally run land comps, I am not that person and I would rather lose the job than oversell it.

**3. Complete workflows I designed and implemented**

- Accuris: enrichment and provenance rebuild, match rates 65% to 89%, API waste down 40%, plus a competitive intelligence engine monitoring 200+ competitors that wrote findings into HubSpot deal records so reps saw them inside the deal instead of a dashboard nobody opens.
- 1up.ai: bi-directional Clay and HubSpot pipeline processing 500+ leads weekly with retry logic and a review checkpoint before any record write, plus a deal stage rebuild that improved forecast accuracy 30%.
- Anchor Browser: cron-scheduled orchestration agent with a Slack approval gate before anything sends.

**4. How I would prepare and structure the sessions**

Before session one I need read access to three real past deals, ideally one you are proud of and one that was messy, plus your existing Skills, your CMA methodology as you would explain it to a new agent, and your branded templates. I do the audit on my own time so we do not spend your paid hours on me reading. Session one: 45 minutes on your two most expensive processes, then straight into building the property record and the CMA Skill, testing against a closing where you already know the answer. Session two: marketing copy suite, listing audit Skill, the Skill-authoring Skill, and a written operating guide for each. We test against known answers, not vibes, so you can see when a Skill is wrong.

**5. What eight to ten hours realistically produces**

Three to four working, tested Skills, not eight half-built ones. Concretely: verified property record plus CMA, the multi-channel marketing copy suite reading from it, a competing-listing audit Skill, and the Skill-authoring Skill. Plus improvements to whichever existing Skills survive the audit, accuracy rules built into each one, operating instructions per Skill, and a prioritized backlog of everything we did not get to, ordered by hours saved against dollars at risk. Anything promising eleven finished Skills in a day is selling you demos.

**6. Availability and time zone**

[FILL IN: earliest availability and time zone]

**7. Confirmation**

I perform all of the work personally. No subcontractors, no handoff, and I will be the person on the screen share.
