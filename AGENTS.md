# English Vocabulary Project - Agent Operating Manual

Date created: 2026-08-07
Current scope: Unit 01-32

This file is the mandatory entry point for every Codex session in this project.

Conversation history is not the source of truth. Project files are the source of
truth. The agent must load the project files before generating, grading, or
updating any quiz.

## 1. Mandatory Startup Checklist

Before generating any quiz, the agent must complete this checklist:

- Read `AGENTS.md`.
- Read `PROJECT_SKILLS.md`.
- Read `NEW_WORD_CANDIDATES.md`.
- Read `HANDOFF.md`.
- Read `ROTATION_STATE.md`.
- Read the latest `RECOVERY_PRIORITIES_*.md`.
- Read the latest `WORD_FORMATION_ADDENDUM_*.md`.
- Read `VOCABULARY_STATE.csv`.
- Read recent quiz history files.
- Detect today's local date.
- Determine weekday and whether today is the last Friday of the month.
- Select the quiz type from the schedule below.

If any required file is missing, stop and report the missing file. Do not
generate a quiz from memory.

## 2. Required Reading Order

Use this order at the start of every quiz session:

1. `AGENTS.md`
2. `PROJECT_SKILLS.md`
3. `NEW_WORD_CANDIDATES.md`
4. `HANDOFF.md`
5. `ROTATION_STATE.md`
6. latest `RECOVERY_PRIORITIES_*.md`
7. latest `WORD_FORMATION_ADDENDUM_*.md`
8. `VOCABULARY_STATE.csv`
9. latest `QUIZ_HISTORY_*.md`
10. monthly reports if the task touches cumulative performance

Only after this sequence may the agent generate a quiz.

## 3. Quiz Schedule Rules

Monday through Thursday:

- Daily Quick
- 12 questions
- Recovery-heavy, with some due words and current unit coverage

Every Friday:

- Weekly Quick
- 30 questions
- Broad weekly rotation, not only the newest unit

Last Friday of each month:

- Monthly Quick / Cumulative Test
- 50 questions
- Replaces the normal Weekly Quick
- Covers the whole active vocabulary bank

Important date rule:

- Never generate a Daily Quick on Friday.
- Never generate a Weekly Quick on the last Friday of the month.
- Always state the exact date used for the decision.

## 4. Quiz Generation Priority

Never choose questions randomly. Select questions in this order:

1. Recovery
2. Due words
3. Current unit coverage
4. Unit Tour
5. Topic Tour
6. Cooldown and long-unseen terms

Avoid repeating the exact same sentence from recent quizzes unless it is an
intentional Recovery check.

Use `PROJECT_SKILLS.md` to shape question style: realistic work, product,
reading, and daily-life contexts; contrast-based distractors; and memory-focused
feedback.

## 5. Daily Quick Structure

Default Daily Quick structure:

- 4-6 Recovery questions
- 3-4 current unit questions
- 1-2 due or older unit questions
- 1-2 Unit Tour / Topic Tour / cooldown checks

Adjust within 12 questions based on `ROTATION_STATE.md`.

## 6. Weekly Quick Structure

Default Weekly Quick structure:

- 7-9 Recovery questions
- 5-6 due or cooldown checks
- 6-8 current/new unit questions
- 4-5 recent unit review questions
- 2-4 Unit Tour / Topic Tour / word-family questions

For Friday 2026-08-07 specifically, generate a Weekly Quick with 30 questions.
It is not the last Friday of August 2026.

## 7. Monthly Quick Structure

Default Monthly Quick structure:

- 50 questions
- Whole active vocabulary bank
- Recovery plus rotation plus word families
- Include prefix traps, collocations, context selection, and older unseen words

After grading a Monthly Quick, create or update the monthly report and reset the
next month rotation priorities.

## 8. Scoring Rules

The learner may answer with uncertainty:

Examples:

- `2?`
- `2? because ...`
- `1B 2? 3C`

Grade these separately:

- final answer
- reasoning
- confidence

Report:

- score
- correct answers
- correct but uncertain answers
- wrong answers
- recovery additions
- cooldown changes
- incidental new-word candidates mentioned by the learner

Correct answers marked with `?` stay on light watch until demonstrated again.

## 9. Grading Feedback Format

When showing quiz results, do not only list wrong question numbers. For every
wrong, unanswered, or unresolved item, include a focused review block:

- Question number.
- The original question sentence, including the blank.
- The learner's answer.
- The correct answer.
- Why the learner's answer is wrong in that context.
- The word or contrast to remember, with a corrected example sentence.

Keep the explanation concise, but make the context distinction explicit. This
is especially important for close traps such as word families, adjective roles,
and terms with similar Vietnamese translations.

If the learner answers only `?` with no final option, mark the item as
unanswered/unresolved and show the correct answer with the same review format.

If the learner says they do not know a non-target word used in a prompt,
sentence, option, or explanation, check whether it exists in
`VOCABULARY_STATE.csv`. If it does not, record it in `NEW_WORD_CANDIDATES.md`
with the context sentence and a short note. Do not automatically add it to the
active vocabulary bank.

## 10. Recovery Rules

Recovery has the highest priority.

Words remain in Recovery until the learner demonstrates stable understanding in
context. Do not remove a word from Recovery after only one correct answer if the
answer was uncertain or the term has repeated confusion.

Recovery priority should decrease gradually:

- P1: must appear early and repeatedly
- P2: include soon, but not every quiz
- P3 / cooldown: occasional checks only

## 11. Update Workflow

When the user says `update` or uploads a new vocabulary file:

1. Read `AGENTS.md`.
2. Read current state files.
3. Read the newly uploaded source/addendum.
4. Merge vocabulary by lemma/unit/context.
5. Add the new unit or terms.
6. Update `VOCABULARY_STATE.csv`.
7. Update `WORD_FORMATION_ADDENDUM_*.md`.
8. Update `ROTATION_STATE.md`.
9. Update the latest recovery file if needed.
10. Review `NEW_WORD_CANDIDATES.md` and promote only user-approved candidates.
11. Do not overwrite the whole vocabulary bank with a patch.

## 12. End-of-Session Checklist

After every graded quiz:

- Update score and quiz history.
- Update Recovery.
- Update Cooldown.
- Update Rotation.
- Update current unit state.
- Record uncertain answers.
- Record incidental unknown non-bank words in `NEW_WORD_CANDIDATES.md`.
- Save the updated project state.

## 13. Things Never To Do

- Never generate a quiz before completing Startup.
- Never rely on chat history as the source of truth.
- Never skip `AGENTS.md`.
- Never skip `PROJECT_SKILLS.md` when generating or grading a quiz.
- Never skip `NEW_WORD_CANDIDATES.md` when generating or grading a quiz.
- Never ignore Recovery.
- Never randomly choose vocabulary.
- Never overwrite the vocabulary database with a small patch.
- Never promote incidental candidate words into the active vocabulary bank
  without user approval.
- Never forget to detect today's date before choosing quiz type.
- Never generate Daily Quick on Friday.
- Never generate Weekly Quick on the last Friday of the month.
- Never repeat yesterday's sentences unless intentionally testing Recovery.
