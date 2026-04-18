---
# Required fields — marked # REQUIRED; never omit or leave null
id: ev-YYYY-NNN                         # REQUIRED e.g. ev-2026-001; unique across the repo
name: ""                                # REQUIRED short descriptive name
type: evidence
evidence_type: ""                       # REQUIRED policy | budget | letter | safeguarding_doc |
                                        #   testimonial | case_study | data | governance_doc |
                                        #   photo_or_media | other
last_updated: YYYY-MM-DD                # REQUIRED
last_verified_date: YYYY-MM-DD          # REQUIRED date this item was last confirmed as current

# Source and provenance
author_or_source: ""                    # REQUIRED person, organisation, or system that produced this
date_of_document: null                  # YYYY-MM-DD | YYYY-MM | YYYY; date the document itself is dated
claim_status: ""                        # REQUIRED confirmed | inferred | speculative
provenance_note: ""                     # brief note on how this item was obtained or generated

# Storage
file_location: ""                       # relative path within repo, or URL if external
file_format: ""                         # e.g. pdf | docx | md | xlsx | link
publicly_available: null                # true | false | unknown

# Reusability
supports_programmes: []                 # list of programme names this evidence supports
supports_funder_types: []               # funder types for which this is particularly useful
                                        # e.g. [youth, safeguarding, education, community]
reusable_in_applications: null          # true | false

# Quality assessment
strength: ""                            # strong | adequate | weak | unknown
strength_rationale: ""                  # why — e.g. "independent third-party letter" or "self-reported only"
limitations: ""                         # known weaknesses, caveats, or things it does not prove

# Expiry
expires: null                           # YYYY-MM-DD if the document expires (e.g. DBS, insurance)
expiry_action: ""                       # what to do when it expires; e.g. "renew DBS via [process]"
---

## Description

<!-- What this evidence item is and what it demonstrates. -->
<!-- Be specific: "Signed letter from [School] confirming partnership for Year 4 programme, dated [date]"
     not just "partner letter". -->

## What this can support in applications

<!-- List the specific claims this evidence legitimately supports. -->
<!-- Example:
     - "WFBA has nominated safeguarding officers" ✓
     - "All tutors hold Enhanced DBS" ✓
     - "School partnership confirmed for September 2026" — this letter does NOT confirm a date; use carefully
-->

## What this cannot support

<!-- Explicitly note what this evidence does not prove, to prevent overclaiming. -->

## Notes

<!-- Any other relevant context, usage history, or caveats. -->
