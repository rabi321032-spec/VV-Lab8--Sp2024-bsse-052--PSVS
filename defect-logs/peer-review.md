# Peer Review Comparison

Inspector: Rabbia Waseem (SP2024/BSSE/052)

## Part A: Classmate swap

Partner: (to be filled after log exchange)
Status: Pending. Log exchange not yet done.

| Item | Count |
|---|---|
| My defects (A) | 26 |
| Partner's defects (B) | pending |
| Found by both | pending |
| Union = A + B - both | pending |
| My detection rate = A / union | pending |

## Part B: Additional defects from a second reviewer


These are defects not already in my log (D01-D26).

| New ID | Req ID | Category | Description | Evidence | Severity | Suggested fix |
|---|---|---|---|---|---|---|
| P01 | S6, S8 | Contradiction | S6 requires boxes to be stored at a safe temperature, but S8 allows a chamber to be warmed to 0°C, which is much warmer than the -18°C limit in S7 and may not be safe for the seeds. | S6 "safe temperature" vs S8 "warmed to 0°C" | High | Define the safe range in S6, and either keep maintenance warming inside it or move boxes out before warming. |
| P02 | S10, S11 | Incompleteness | It is not stated whether a redeposited box restores the depositor's withdrawal quota for that year. Without this, S10 cannot be applied after a redeposit. | S10 "at most 20% ... per year" vs S11 "may be redeposited" | Medium | State whether a redeposit reduces the count of boxes withdrawn that year. |
| P03 | S9 | Ambiguity | Viability is a property of seed samples, but the vault stores and tracks sealed boxes. It is unclear whether a flag applies to the sample, the box, or only part of the box. | "Seed samples with low viability shall be flagged" | Medium | State the flagging unit and what happens to the other samples in the same box. |
| P04 | S2, S3, S5, S8 | Ambiguity | The requirements mix "shall", "can", "may" and plain statements ("hold at most"), so it is unclear which are mandatory and which are optional. | S2 "can hold", S5 "may release", S8 "may be warmed" | Low | Use "shall" for mandatory behaviour and "may" only for permitted options. |
