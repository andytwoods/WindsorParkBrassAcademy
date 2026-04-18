---
# Required fields — marked # REQUIRED; never omit or leave null
name: ""                                # REQUIRED
type: programme
status: ""                              # REQUIRED planned | active | paused | complete
last_updated: YYYY-MM-DD                # REQUIRED
last_verified_date: YYYY-MM-DD          # REQUIRED

# Description
description: ""                         # REQUIRED one-sentence summary
delivery_model: ""                      # REQUIRED brief description of how it runs
start_date: null                        # YYYY-MM-DD | "YYYY-MM" | "unknown"
frequency: ""                           # one-off | annual | ongoing | unknown

# Delivery readiness
# REQUIRED — complete before treating this programme as fundable
delivery_readiness: ""                  # REQUIRED ready | nearly_ready | in_development | blocked
delivery_readiness_rationale: ""        # REQUIRED one sentence explaining the assessment

critical_prerequisites:                 # REQUIRED list all hard dependencies before delivery can begin
  - description: ""                     # what is needed
    status: ""                          # confirmed | in_progress | not_started | blocked
    blocking: null                      # true | false — does absence block delivery entirely?
    due_date: null                      # YYYY-MM-DD | null
    notes: ""

# Beneficiaries
target_beneficiaries: []               # REQUIRED list: e.g. ["Year 4 pupils", "complete beginners"]
beneficiary_age_range: ""              # e.g. "8–9" or "all ages"
geography: ""                          # REQUIRED delivery geography
estimated_participants_per_year: null  # integer; null if unknown

# Budget
estimated_total_budget: null           # £ integer per year; null if unknown
budget_breakdown_available: false      # true | false
fundable_components: []                # cost lines suitable for grant applications
                                       # e.g. ["plastic instruments", "tutor time", "transport"]

# Outcomes and evidence
primary_outcomes: []                   # REQUIRED what the programme is intended to achieve
evidence_available: []                 # evidence items already held (ev- ID or brief description)
evidence_gaps: []                      # evidence items needed but not yet available

# Funding fit
strongest_funder_types: []             # funder types most likely to support this
linked_opportunities: []               # opportunity IDs currently targeting this programme
---

## Programme narrative

<!--
2–3 paragraphs describing the programme in terms suitable for adaptation into application text.
Write for a funder who knows nothing about WFBA.
Cover: what it is, who it serves, why it matters, what it does, and what happens next for participants.
Do not overclaim on evidence not yet available.
-->

## Impact pathway

<!--
How does participation lead to the claimed outcomes?
Keep this proportionate to what evidence WFBA currently has.
Mark any steps that are claimed but not yet evidenced.
-->

## Sustainability note

<!--
How does grant funding for this programme connect to non-grant income,
member subscriptions, school contributions, or self-sustaining activity?
Applications should show how the grant creates or stabilises a wider participation pathway,
not just pays for a one-off activity.
-->

## Operational readiness checklist

<!--
What needs to be in place before delivery can begin?
Check each item and date it when confirmed.
These should mirror the critical_prerequisites in the frontmatter.

- [ ] School or venue partner confirmed
- [ ] Tutor(s) confirmed
- [ ] Safeguarding requirements met for this programme
- [ ] Instruments available or funded
- [ ] Budget confirmed
- [ ] Parental consent/communication plan in place (if children involved)
- [ ] Any required insurance or policy in place
-->
