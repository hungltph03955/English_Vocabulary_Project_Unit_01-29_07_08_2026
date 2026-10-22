# Tactics Rotation State

Date initialized: Monday 2026-10-12
Last updated: Thursday 2026-10-22 after WF55 import; last grading DQ-2026-10-22
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
- Current source unit: finishing Tactics Unit 04; first two Unit 05 anchors reserved
- Current cursor (next unscheduled target): `TACTICS-U05-003`
- Initial Daily Quick quota: 2 Tactics targets
- Initial Weekly Quick quota: 6 Tactics targets
- Scheduled targets for the next valid Weekly Quick:
  - `TACTICS-U04-002` - `chat` (verb)
  - `TACTICS-U04-003` - `newspaper` (noun)
  - `TACTICS-U04-005` - `text` (verb)
  - `TACTICS-U04-015` - canonical `new year`, printed `New Year` (proper noun)
  - `TACTICS-U05-001` - `airport` (noun)
  - `TACTICS-U05-002` - `appointment` (noun)
- Next expected quiz: Friday 2026-10-23 Weekly Quick, 30 questions
- Last Tactics quiz: `DQ-2026-10-22`, Q5/Q9/Q10, 3/3 correct without
  uncertainty; includes existing boot Recovery and two first-practice targets

The DQ-2026-10-22 batch is graded and closed. All five T01, T02, and T03
Pass-A anchors are now tested. T04 has one tested and its remaining four
reserved; T05 has two reserved. Next unscheduled cursor: U05-003.

The six next scheduled rows remain `queued/P2` in the main CSV until grading.
Their scheduled eligibility exists only in this file and must be recorded in
the next quiz selection map. All six have verified Tier-A source rows and
checked contextual definitions in the map and CSV. Printed New Year is
retained with lowercase canonical new year. Printed boots remains mapped
to boot in its Recovery record.

Completed quiz: `DQ-2026-10-22`, exact source
`QUIZ_2026-10-22_DAILY.md`. Q5 boot is a confident first correction and
stays recovery/P2. Q9 dress and Q10 cereal pass first checks and move
queued -> new_unit/P2; normal review no earlier than 2026-10-29.
Q8 graduate was missed for WF54 only; its shared canonical row becomes
Recovery P2, but U06-009 remains unscheduled and untested. Bank: 1,390 rows,
660 nonqueued and 730 queued. No quiz is pending; the Friday batch is scheduled.

Completed quiz: `DQ-2026-10-19`, exact source
`QUIZ_2026-10-19_DAILY.md`. Q9 TACTICS-U03-003 boot (printed boots)
was wrong and uncertain, selected outfits, so its canonical state becomes
recovery/P2. Q10 TACTICS-U03-004 comfortable passed first practice and
becomes new_unit/P2. Next scheduled pair remains queued; no unscheduled
queued row is promoted. Bank: 1,373 rows, 640 nonqueued and 733 queued.

Completed quiz: `WQ-2026-10-16`, exact source
`QUIZ_2026-10-16_WEEKLY.md`. Q15-Q20 tested the six scheduled IDs. Five
confident answers moved queued -> new_unit/P2; Q16 `almost` moved queued
-> recovery/P2 because it was correct but uncertain. Next unscheduled
cursor is U03-005. No unscheduled queued row was promoted.

The previous issued quiz `DQ-2026-10-15` has been graded from
`QUIZ_2026-10-15_DAILY.md`. `Gym` is now new_unit/P2; `actress` is now
Recovery P2 after the supervisor-for-performer error.

## Grading Ledger - Thursday 2026-10-22

Exact source: `QUIZ_2026-10-22_DAILY.md`.

| Target ID | Lemma | Q | Final / key | Result | Confidence | Error type | Current state | Earliest normal review |
|---|---|---:|---|---|---|---|---|---|
| TACTICS-U03-003 | boot; printed boots | 5 | D / D | correct; first correction | no uncertainty marker | none this check | recovery/P2 | Recovery due |
| TACTICS-U03-005 | dress | 9 | C / C | correct; first check | no uncertainty marker | none | new_unit/P2 | 2026-10-29 |
| TACTICS-U04-001 | cereal | 10 | A / A | correct; first check | no uncertainty marker | none | new_unit/P2 | 2026-10-29 |

Graduate Q8 was WF54-only and is not credited as a Tactics check. Next six
verified Weekly targets remain queued/P2; next unscheduled cursor U05-003.
Bank: 1,390 rows, 660 nonqueued and 730 queued. No Tactics cooldown addition.

## Grading Ledger - Monday 2026-10-19

Exact source: `QUIZ_2026-10-19_DAILY.md`.

| Target ID | Lemma | Q | Final / key | Result | Confidence | Error type | Current state | Earliest normal review |
|---|---|---:|---|---|---|---|---|---|
| TACTICS-U03-003 | boot; printed boots | 9 | D / B | wrong; selected outfits | uncertain | footwear versus clothing set | recovery/P2 | Recovery due |
| TACTICS-U03-004 | comfortable | 10 | A / A | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-26 |

The learner correctly understood knee-high, but missed the specific rubber
footwear. Selected outfit also enters Recovery P2. Comfortable has a first
confident success, not stable mastery. Next scheduled verified targets
U03-005 dress and U04-001 cereal remain queued/P2; cursor U04-002.
Bank: 1,373 rows, 640 nonqueued and 733 queued.

## Grading Ledger - Friday 2026-10-16

Exact source: `QUIZ_2026-10-16_WEEKLY.md`.

| Target ID | Lemma | Q | Final / key | Result | Confidence | Error type | Current state | Earliest normal review |
|---|---|---:|---|---|---|---|---|---|
| TACTICS-U02-002 | age | 15 | D / D | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-23 |
| TACTICS-U02-003 | almost | 16 | C / C | correct | uncertain; reasoning sound | none | recovery/P2 light watch | Recovery due |
| TACTICS-U02-004 | blond | 17 | A / A | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-23 |
| TACTICS-U02-005 | boyfriend | 18 | B / B | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-23 |
| TACTICS-U03-001 | blouse | 19 | D / D | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-23 |
| TACTICS-U03-002 | bodybuilder; printed body-builder | 20 | C / C | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-23 |

Main bank after grading: 1,373 rows, 638 nonqueued and 735 queued.
Next scheduled verified pair: U03-003 `boot` and U03-004 `comfortable`.
Both remain queued and untested; next unscheduled cursor U03-005.

## Grading Ledger - Thursday 2026-10-15

Exact source: `QUIZ_2026-10-15_DAILY.md`.

| Target ID | Lemma | Q | Final / key | Result | Confidence | Error type | Current state | Earliest normal review |
|---|---|---:|---|---|---|---|---|---|
| TACTICS-U01-005 | gym | 9 | A / A | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-22 |
| TACTICS-U02-001 | actress | 10 | D / C | wrong; selected supervisor | no uncertainty marker | performer versus manager | recovery/P2 | Recovery due |

Main bank after grading: 1,357 rows, 616 nonqueued and 741 queued. The
next six verified targets remain queued and untested. `Actress` is eligible
for Recovery in a new context when due; do not count the next scheduled
unseen batch as already mastered.

The previous issued quiz `DQ-2026-10-14` has been graded from
`QUIZ_2026-10-14_DAILY.md`. `Department` is on P2 Recovery because its
correct answer was uncertain; canonical `forget` is now new_unit/P2.

## Grading Ledger - Wednesday 2026-10-14

Exact source: `QUIZ_2026-10-14_DAILY.md`.

| Target ID | Lemma | Q | Final / key | Result | Confidence | Error type | Current state | Earliest normal review |
|---|---|---:|---|---|---|---|---|---|
| TACTICS-U01-003 | department | 9 | B / B | correct | uncertain; reasoning correct | none | recovery/P2 light watch | Recovery due; no standard seven-day repeat requirement |
| TACTICS-U01-004 | forget; printed forgotten | 10 | A / A | correct | no uncertainty marker | none | new_unit/P2 | 2026-10-21 |

No Tactics target was answered incorrectly. Q9's uncertainty is tracked
separately from its correct final answer. Both targets are now nonqueued;
the next batch remains queued until it is tested. Main bank at grading: 1,342 rows,
598 nonqueued and 744 queued. T01 Pass-A progress: 5/5 tested. T02 Pass-A
progress: 0/5 tested, 1 reserved next.

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
| T01 | 22 | 22 | 21 | 1 | 0 | 12 | 6 | 4 | Pass-A anchors complete |
| T02 | 30 | 30 | 30 | 0 | 0 | 22 | 7 | 1 | Pass-A anchors complete |
| T03 | 34 | 34 | 31 | 1 | 2 | 31 | 3 | 0 | Pass-A anchors complete |
| T04 | 22 | 21 | 20 | 1 | 1 | 7 | 12 | 3 | U04-001 tested; U04-002, 003, 005, 015 reserved |
| T05 | 36 | 36 | 36 | 0 | 0 | 22 | 8 | 6 | U05-001/002 reserved; U05-003 to U05-005 remain |
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

Unit 55 graph import on 2026-10-22 adds 10 Word Formation rows and reuses
existing geography. It does not change a Tactics canonical row, source ID,
result, or eligibility. The six verified targets already scheduled for
Friday remain queued; next unscheduled cursor stays U05-003. Unit 55
becomes primary current Word Formation coverage.

Unit 54 grad/gress import on 2026-10-19 activates shared canonical
graduate (printed Tactics graduated) as a WF54 book word, using its existing
row rather than adding a duplicate. Its canonical noun/verb senses are
normalized for the learner's explicit WF54 source. TACTICS-U06-009 remains
unscheduled and untested; this activation grants WF54 practice coverage,
not a tested Tactics source result. Printed source forms/POS remain in the
map. After the 2026-10-22 WF54 miss, graduate is Recovery P2; U06-009 is
still untested. The dress/cereal pair is closed; next Weekly batch and
U05-003 cursor are listed above.

Unit 52 `gen` import on 2026-10-14 activated existing Tactics T22 lemma
`generous` as a Word Formation book word without creating a duplicate.
The T22 source row `TACTICS-U22-005` remains unscheduled and untested; use
`generous` for WF52 coverage only until that Tactics target is selected by
the Tactics rotation. The initial import counts above remain historical.
Current bank after WF55 import: 1,400 rows, 670 nonqueued and
730 queued. Six verified rows are scheduled for Friday's Weekly Quick;
all stay queued until graded. Next unscheduled cursor U05-003. Older
ledger and initial-import counts above remain historical.

Transition phase while the current Word Formation unit needs first practice
(currently Unit 55; Units 54/53/52/51 remain recent review/Recovery):

- Daily Quick: 5 Recovery, 3 Unit 55, 2 Tactics, 1 recent Word Formation, 1 cooldown.
- Weekly Quick: 8 Recovery, 6 Unit 55/current, 6 Tactics, 6 due/recent, 4 tour/family.

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
