# Tactics Rotation State

Date initialized: Monday 2026-10-12
Last updated: Tuesday 2026-10-13 after Unit 51 import; last grading DQ-2026-10-13
Source: Tactics Vocabulary Index images, pages 110-112
Source units: Tactics 01-24
Detailed mapping: `TACTICS_IMPORT_MAP.csv`
Main vocabulary state: `VOCABULARY_STATE.csv`

## Import Summary

- Printed source rows: 824
- Canonical groups after normalization: 770
- Existing-bank source rows cross-referenced: 22
- Repeated source rows combined: 54
- New canonical rows added to the main bank: 748
- New-row status: `queued/P2`
- Main bank after merge: 1,331 rows
- OCR review holds: `sneak` and `driven`
- Candidate promotions: none

`queued` means stored in the main vocabulary bank but not eligible as a quiz
answer or distractor. An item becomes eligible only when this rotation selects
it and its source text has `ocr_status=verified`.

## Current Cursor

- Current pass: A - anchor words
- Current source unit: Tactics Unit 01
- Current cursor (next unscheduled target): `TACTICS-U01-005`
- Initial Daily Quick quota: 2 Tactics targets
- Initial Weekly Quick quota: 6 Tactics targets
- Scheduled targets for the next valid Daily Quick:
  - `TACTICS-U01-003` - `department` (noun)
  - `TACTICS-U01-004` - canonical `forget` (verb); printed `forgotten` (past participle / adjective)
- Next expected quiz: Wednesday 2026-10-14, Daily Quick
- Last Tactics quiz: `DQ-2026-10-13`, Q9-Q10, 2/2 without uncertainty markers

The prior batch `TACTICS-U01-001` / `TACTICS-U01-002` is graded and closed.
The cursor advances to U01-005 because U01-003/U01-004 are now explicitly
reserved as the next verified batch, not because they were already tested.

The next scheduled rows remain `queued/P2` in the main CSV until grading. Their
scheduled eligibility exists only in this file and must be recorded in the
quiz selection map. Canonical POS and contextual definitions have been checked;
the source mapping preserves the printed `forgotten` form and its source POS.

## Grading Ledger - Tuesday 2026-10-13

Exact source: `QUIZ_2026-10-13_DAILY.md`.

| Target ID | Lemma | Q | Final / key | Result | Confidence | Error type | Current state | Earliest normal review |
|---|---|---:|---|---|---|---|---|---|
| TACTICS-U01-001 | accounting | 9 | A / A | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-20 |
| TACTICS-U01-002 | assignment | 10 | C / C | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-20 |

Reasoning was not supplied. Unmarked correct choices use the established
confident-success state convention; confidence is not independently verified.
Two canonical targets have been tested; both succeeded on their first check.
No Tactics Recovery addition and no new Tactics cooldown item.
Main bank at grading: 1,331 rows, 585 nonqueued and 746 queued.
T01 Pass-A anchor progress: 2/5 tested; 2 reserved next; `gym` remains unseen.
After the five T01 anchors are tested, continue round-robin to T02.

## Unit Queue

Counts below describe the initial import. The last column tracks remaining
Pass-A anchors for the current unit; exact scheduled eligibility is above.

| Unit | Printed | Canonical in unit | New primary rows | Cross-reference | Combined repeats | Tier A | Tier B | Tier C | Next verified Tier-A batch |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---|
| T01 | 22 | 22 | 21 | 1 | 0 | 12 | 6 | 4 | U01-003 to U01-005 |
| T02 | 30 | 30 | 30 | 0 | 0 | 22 | 7 | 1 | U02-001 to U02-005 |
| T03 | 34 | 34 | 31 | 1 | 2 | 31 | 3 | 0 | U03-001 to U03-005 |
| T04 | 22 | 21 | 20 | 1 | 1 | 7 | 12 | 3 | U04-001, 002, 003, 005, 015 |
| T05 | 36 | 36 | 36 | 0 | 0 | 22 | 8 | 6 | U05-001 to U05-005 |
| T06 | 43 | 43 | 39 | 3 | 1 | 27 | 14 | 2 | U06-001 to U06-005 |
| T07 | 37 | 37 | 34 | 2 | 1 | 23 | 10 | 4 | U07-002 to U07-006 |
| T08 | 29 | 29 | 29 | 0 | 0 | 12 | 15 | 2 | U08-001 to U08-005 |
| T09 | 41 | 41 | 38 | 3 | 0 | 26 | 15 | 0 | U09-001 to U09-005 |
| T10 | 28 | 28 | 26 | 0 | 2 | 19 | 8 | 1 | U10-001, 002, 003, 005, 006 |
| T11 | 25 | 25 | 22 | 0 | 3 | 11 | 7 | 7 | U11-001, 003, 004, 006, 007 |
| T12 | 40 | 40 | 37 | 2 | 1 | 23 | 12 | 5 | U12-001 to U12-005 |
| T13 | 53 | 53 | 52 | 0 | 1 | 41 | 12 | 0 | U13-001 to U13-005 |
| T14 | 28 | 28 | 26 | 0 | 2 | 7 | 8 | 13 | U14-001 to U14-005 |
| T15 | 32 | 32 | 31 | 0 | 1 | 17 | 11 | 4 | U15-002 to U15-006 |
| T16 | 28 | 28 | 23 | 0 | 5 | 19 | 9 | 0 | U16-001, 002, 003, 005, 007 |
| T17 | 35 | 35 | 30 | 1 | 4 | 15 | 18 | 2 | U17-003, 005, 008, 009, 015 |
| T18 | 30 | 30 | 27 | 0 | 3 | 19 | 9 | 2 | U18-001, 002, 003, 004, 006 |
| T19 | 46 | 46 | 33 | 6 | 7 | 24 | 19 | 3 | U19-002, 004, 005, 006, 007 |
| T20 | 41 | 41 | 35 | 1 | 5 | 30 | 11 | 0 | U20-001, 002, 003, 005, 006 |
| T21 | 25 | 25 | 20 | 1 | 4 | 10 | 15 | 0 | U21-001, 002, 004, 005, 006 |
| T22 | 39 | 39 | 38 | 0 | 1 | 23 | 16 | 0 | U22-001, 003, 004, 005, 006 |
| T23 | 32 | 32 | 26 | 0 | 6 | 25 | 7 | 0 | U23-001, 002, 003, 008, 009 |
| T24 | 48 | 47 | 44 | 0 | 4 | 34 | 14 | 0 | U24-001 to U24-005 |

## Pass Order

1. Pass A: five verified Tier-A anchor words per unit, T01 through T24.
2. Pass B: remaining verified Tier-A words, five to eight per unit.
3. Pass C: Tier-B collocations, noun phrases, verb phrases, and phrasal verbs.
4. Pass D: Tier-C questions, sentences, and functional expressions.

Advance round-robin by unit. Do not finish every item in one large unit before
moving to the next unit.

## Selection Rules

1. Global Recovery keeps the highest priority.
2. Select Tactics Recovery due items before unseen Tactics items.
3. Select unseen items from the current pass and current source unit.
4. Before scheduling, verify the canonical form, POS, and meanings in the
   mapping/addendum; replace a compact import gloss with a contextual English
   definition for every scheduled target.
5. Skip `ocr_status=needs_review` until the source is manually confirmed.
6. Do not use `status=queued` outside the scheduled batch.
7. Do not repeat a Tactics target within seven days unless it is Recovery.
8. Do not select two forms of one lemma in the same quiz unless the question
   intentionally tests that contrast.
9. Use no more than two unseen Tactics distractors in one question.
10. Preserve the exact source unit and `target_id` in each quiz selection map.

## State Transitions After Grading

- Correct confidently on first eligible check: `queued -> new_unit/P2`.
- Correct but uncertain: `queued/new_unit -> recovery/P2`.
- Wrong or unresolved first check: `queued/new_unit -> recovery/P2`.
- Repeated meaning or word-family error: `recovery/P2 -> recovery/P1`.
- Stable confident retrieval in varied contexts: `new_unit/recovery -> cooldown/P3`.

The detailed mapping row retains the printed form and source. The main CSV row
stores the canonical lemma or phrase.

## Quick Allocation

Current update: Unit 51 `funct` adds 11 nonqueued Word Formation rows on
2026-10-13. The bank is now 1,342 rows, 596 nonqueued and 746 queued.
This import does not change the Tactics mapping, tested ledger, scheduled
department/forget batch, seven-day review dates, or unscheduled cursor U01-005.

Transition phase while the current Word Formation unit needs first practice
(currently Unit 51; Unit 50 remains recent review/Recovery):

- Daily Quick: 5 Recovery, 3 Unit 51, 2 Tactics, 1 Unit 50/recent, 1 cooldown.
- Weekly Quick: 8 Recovery, 6 Unit 51/current, 6 Tactics, 6 due/recent, 4 tour/family.

Steady phase after current Word Formation first-practice coverage:

- Daily Quick: 5 Recovery, 4 Tactics, 2 due Word Formation, 1 cooldown.
- Weekly Quick: 8 Recovery, 7 Tactics, 6 due/cooldown, 5 recent Word Formation,
  and 4 Topic Tour/expression/family checks.

## Grading Update Checklist

After every graded quiz containing Tactics items:

- Record quiz ID, question number, final answer, confidence, and error type.
- Update the canonical row in `VOCABULARY_STATE.csv`.
- Update the matching mapping row and this cursor.
- Move wrong or uncertain items into Recovery.
- Do not promote a queued item that was only used as an unseen distractor.
- Save the next verified batch before generating the following quiz.
