# Defect Taxonomy

| # | Category | Definition | Example |
|---|---|---|---|
| 1 | Ambiguity | A statement can be read in more than one valid way. | "Registered depositor": registered with whom, and how? |
| 2 | Vagueness | Uses terms with no measurable value. | "The system shall respond quickly." |
| 3 | Incompleteness | A needed case, actor, value or error path is missing. | A withdrawal requirement that does not say what happens if the box is not found. |
| 4 | Contradiction | Two statements cannot both be true. | "Never exceed 5 users" and "allow 10 users at peak". |
| 5 | Non-verifiability | No practical test or inspection can show the requirement is met. | "The interface shall be user friendly." |
| 6 | Redundancy | The same thing is stated more than once. | Two requirements that both say passwords must be hashed. |
| 7 | Infeasibility | Cannot be achieved under the stated limits or in practice. | "Zero downtime forever" on a single server. |
| 8 | Untraceability | No source, rationale or link to other artifacts. | A requirement with no owner or origin. |

## Severity scale

| Severity | Meaning |
|---|---|
| High | May cause wrong or unsafe behaviour, or blocks modelling |
| Medium | Causes gaps or confusion but has a workaround |
| Low | Wording or housekeeping issue |

## Status values

Open, Fixed, Rejected, Deferred
