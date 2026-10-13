# Tactics Quick Integration Dry Run - 2026-10-13

Status: validation only; do not grade as a learner quiz
Intended schedule shape: Tuesday Daily Quick, 12 questions
Purpose: verify Tactics queue eligibility, selection mapping, and allocation

## Allocation

- Q1-Q5: 5 Recovery questions
- Q6-Q8: 3 current Unit 50 questions
- Q9-Q10: 2 scheduled Tactics Unit 01 targets
- Q11: 1 due Unit 49 check
- Q12: 1 cooldown/tour check

## Questions

1. The newsreader practiced her ______ so she could pronounce every guest's name clearly.
   A. dictionary | B. dictation | C. diction | D. dictate

2. The safety handle uses a material that is not electrically ______.
   A. conduction | B. conductive | C. conductor | D. conduct

3. The committee released a ______ recommendation while it waited for final approval from the minister.
   A. semiannual | B. semiformal | C. semi-permanent | D. semiofficial

4. Battery ______ increased after the factory added a second assembly line.
   A. production | B. productive | C. product | D. produce

5. Describing long-term burnout as "just being tired" is too ______.
   A. reduction | B. reductive | C. reduce | D. productive

6. All contractors must ______ to the updated safety standard.
   A. conformity | B. conformance | C. conform | D. conformist

7. The workshop handout was clear and ______, with practical examples on every page.
   A. informative | B. information | C. inform | D. misinformation

8. The company completed a digital ______, replacing paper forms with an online platform.
   A. transform | B. transformer | C. reformation | D. transformation

9. Mai works in the finance department and is studying ______ to prepare financial records.
   A. accounting | B. production | C. credibility | D. diction

10. The manager gave each new employee an ______ to complete before Friday.
    A. indication | B. credential | C. provision | D. assignment

11. The therapist asked him to ______ his fingers slowly after removing the bandage.
    A. flexor | B. flex | C. flexibility | D. flexibly

12. As a safety ______, the laboratory stored a backup sample in another freezer.
    A. preview | B. provision | C. precaution | D. protection

## Answer Key and Selection Map

| Q | Answer | Target | Source | Status at selection | Allocation |
|---|---|---|---|---|---|
| 1 | C | diction | Unit 47 | recovery/P1 | Recovery |
| 2 | B | conductive | Unit 48 | recovery/P1 | Recovery |
| 3 | D | semiofficial | Unit 34 | recovery/P1 | Recovery |
| 4 | A | production | Unit 48 | recovery/P1 | Recovery |
| 5 | B | reductive | Unit 48 | recovery/P1 | Recovery |
| 6 | C | conform | Unit 50 | new_unit/P2 | Current unit |
| 7 | A | informative | Unit 50 | new_unit/P2 | Current family |
| 8 | D | transformation | Unit 50 | new_unit/P2 | Current family |
| 9 | A | accounting | TACTICS-U01-001 | queued/P2; explicitly scheduled | Tactics |
| 10 | D | assignment | TACTICS-U01-002 | queued/P2; explicitly scheduled | Tactics |
| 11 | B | flex | Unit 49 | recovery/P2 | Due recent unit |
| 12 | C | precaution | Unit 31 | cooldown/P3 | Cooldown/tour |

## Dry-Run Acceptance Checks

- Exactly 12 questions: passed.
- Allocation is 5 Recovery + 3 Unit 50 + 2 Tactics + 1 Unit 49 + 1 cooldown.
- Both Tactics answer targets exist in `TACTICS_IMPORT_MAP.csv`.
- Both Tactics targets are listed as scheduled in `TACTICS_ROTATION_STATE.md`.
- No other queued Tactics item appears as an answer or distractor.
- No OCR-hold target appears.
- Every correct answer exists in `VOCABULARY_STATE.csv`.
- Tactics target IDs are preserved in the selection map.
- Question sentences are new and do not repeat the 2026-10-09 or 2026-10-12 wording.

Automated result: passed. The only queued option terms are the two scheduled
targets (`accounting` and `assignment`); both target IDs exist, both are listed
in the rotation, every answer target exists in the main CSV, and no OCR-hold
item appears.
