---
# Required fields — marked # REQUIRED; never omit or leave null
name: ""                               # REQUIRED
type: funder
funder_type: ""                        # REQUIRED charitable_trust | local_authority | lottery |
                                       #   arts_council | government | corporate | university | other
last_updated: YYYY-MM-DD               # REQUIRED
last_verified_date: YYYY-MM-DD         # REQUIRED
source_url: ""                         # REQUIRED URL where this funder's scheme information lives
provenance: ""                         # how this funder was identified

# Geography
geography_scope: ""                    # REQUIRED local | regional | national | international
geography_areas: []                    # specific councils, regions, or postcodes if applicable

# Focus
primary_focus: []                      # REQUIRED e.g. [youth, music, education, community, wellbeing]
exclusions: []                         # what this funder explicitly will not fund
                                       # e.g. ["individuals", "organisations with income over £X",
                                       #        "activities outside Surrey"]
eligible_organisation_types: []        # e.g. [registered_charity, community_group, CIC]
charity_registration_required: null    # REQUIRED true | false | unclear
min_income_required: null              # £ integer; null if no minimum
max_income_allowed: null               # £ integer; null if no maximum
notes_on_eligibility: ""

# Grant characteristics
typical_grant_min: null                # £ integer; null if unknown
typical_grant_max: null                # £ integer; null if unknown
grant_size_notes: ""                   # e.g. "average award £3k–£8k based on past grants list"
reporting_burden: ""                   # light | moderate | heavy | unknown
reporting_notes: ""                    # e.g. "one narrative report at 6 months, one at close"
unsolicited_approaches: null           # yes | no | invitation_only | unknown
unsolicited_notes: ""                  # e.g. "EOI required before full application"

# Timing
next_expected_round: null              # YYYY-MM-DD | "rolling" | "unknown"
round_frequency: ""                    # annual | biannual | rolling | irregular | unknown
deadline_notes: ""                     # e.g. "historically opens March, closes June"

# Active schemes run by this funder
active_schemes: []                     # opportunity IDs; list all known schemes

# Relationship
relationship_status: ""                # REQUIRED no_contact | warm | applied | funded | declined
key_contact: ""
last_contact_date: null                # YYYY-MM-DD
---

## About this funder

<!-- Brief description: mission, stated priorities, geographic focus, typical grantees. -->
<!-- Include source URL and verification date for any specific claims. -->

## WFBA fit assessment

<!--
How well do WFBA's current programmes align with this funder's stated priorities?
Note specific strengths, weaknesses, and any eligibility risks.
Be honest: a weak fit should be noted here, not buried or glossed over.
-->

## Application intelligence

<!--
Anything useful about how this funder works in practice:
- whether they fund first-time applicants
- whether a relationship or introduction helps
- whether they expect a particular framing or language
- whether past funded projects give a signal about their real priorities
- any known frustrations or requirements not stated in guidelines
Include source and date for any intelligence beyond the public guidelines.
-->

## Relationship history

<!--
Log of any contact, applications, correspondence, or relevant intelligence.
Format: YYYY-MM-DD — [action or event] — [outcome or next step]
-->
