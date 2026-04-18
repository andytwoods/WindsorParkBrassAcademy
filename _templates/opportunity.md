---
# Required fields — all must be present; leave null/empty rather than omitting
id: opp-YYYY-NNN                      # e.g. opp-2026-001; unique across the repo
name: ""
type: opportunity
funder: ""                            # funder name; must match a file in funders/
funder_type: ""                       # charitable_trust | local_authority | lottery | arts_council | government | corporate | university | other
state: ""                             # apply_now | apply_when_registered | monitor | relationship_build | parked | rejected
state_rationale: ""                   # one sentence explaining the state assignment
last_updated: YYYY-MM-DD
last_verified_date: YYYY-MM-DD        # date eligibility facts were last checked against source
provenance: ""                        # URL or named source where this opportunity was confirmed

# Funding details
amount_min: null                      # £ integer; null if unknown
amount_max: null                      # £ integer; null if unknown
deadline: null                        # YYYY-MM-DD | "rolling" | "unknown"
funding_cycle: ""                     # annual | rolling | one-off | unknown

# Eligibility
geography: ""                         # e.g. "Runnymede / Surrey" or "national"
charity_registration_required: null   # true | false | unclear
legal_form_required: ""               # e.g. "registered charity only" or "any non-profit"
eligibility_summary: ""               # brief plain-English summary of who can apply

# Qualification gates (record outcome of Stage 1 check)
gate_legal_form: ""                   # pass | fail | unclear
gate_charity_registration: ""         # pass | fail | unclear | not_required
gate_geography: ""                    # pass | fail | unclear
gate_beneficiary: ""                  # pass | fail | unclear
gate_programme: ""                    # pass | fail | unclear
gate_funding_size: ""                 # pass | fail | unclear
gate_open_status: ""                  # open | closed | upcoming | unknown
gate_deadline_realism: ""             # pass | fail | unclear
gate_evidence: ""                     # pass | fail | unclear

# Priority score (Stage 2 — only for apply_now / apply_when_registered)
score_mission_fit: null               # 1–5
score_programme_fit: null             # 1–5
score_evidence_readiness: null        # 1–5
score_likelihood_of_success: null     # 1–5
score_grant_size_fit: null            # 1–5
score_relationship_value: null        # 1–5
score_repeat_funding_potential: null  # 1–5
score_urgency: null                   # 1–5
score_application_burden: null        # 1–5 (1 = light, 5 = very heavy)
score_restriction_cost: null          # 1–5 (1 = unrestricted, 5 = heavily restricted)
score_confidence: null                # 1–5
score_rationale: ""                   # brief written rationale; required alongside scores

# Linked objects
linked_programmes: []                 # programme names this opportunity could fund

# Action
next_action: ""
next_action_due: null                 # YYYY-MM-DD
blocker: ""                           # required if state = parked; specific gate or issue blocking progress
unblock_condition: ""                 # required if state = parked; what would change this state
review_date: null                     # YYYY-MM-DD — required if state = parked or monitor
---

## Notes

<!-- Free text: research notes, eligibility detail, context. -->

## Eligibility evidence

<!-- Record source, date, and exact wording for each key eligibility claim. -->
<!-- Example: "Must be a registered charity. Source: [fund guidelines URL], checked 2026-04-18." -->

## Application history

<!-- Log any prior submissions to this fund with dates and outcomes. -->

## State history

<!-- Log each state change with date and reason. -->
<!-- Example: "2026-04-18: set to monitor — fund open but charity registration required; will revisit on registration." -->
