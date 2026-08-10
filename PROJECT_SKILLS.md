# Project Skills - English Vocabulary Project

Date created: 2026-08-07
Scope: Unit 01-29

This file defines project-specific learning and quiz-design skills. It is not a
replacement for `VOCABULARY_STATE.csv`, `ROTATION_STATE.md`, or Recovery files.
Use it to decide how to read context, build memory, generate Quick questions,
and explain mistakes.

## 1. Reading Skill

Goal: train the learner to identify meaning from context, not from isolated
translation.

When generating or grading questions:

- Focus on the subject, object, and situation around the blank.
- Use collocations that sound natural in work and daily life.
- Test the role of the word in the sentence: noun, verb, adjective, adverb, or
  phrasal verb.
- For close traps, make the context cue visible but not too obvious.
- Avoid definition-only prompts unless the item is new and needs first exposure.

Useful context cues:

- People noticing details: `observant`, `perceptive`
- Facts and fairness: `objective`
- Measurable or visible changes: `observable`
- Emotion suddenly expressed: `outburst`
- Disease or violence suddenly spreading: `outbreak`
- Convincing someone: `persuade`, `persuasive`
- Point of view: `perspective`
- Public understanding or impression: `perception`

## 2. Memory Skill

Goal: turn mistakes into stable memory through contrast and repeated context.

When the learner misses a word:

- Store the mistake as a contrast, not as a single isolated word.
- Re-test the same contrast with a new sentence, not the exact same sentence,
  unless it is an intentional Recovery check.
- Keep correct-but-uncertain answers on light watch.
- Do not remove a repeated confusion from Recovery after only one correct
  answer.
- Prefer short corrected examples that can be remembered as chunks.

Memory chunk examples:

- `illegible handwriting`: writing that cannot be read.
- `illiterate adult`: a person who cannot read or write.
- `angry outburst`: a sudden expression of anger.
- `flu outbreak`: sudden spread of illness.
- `public perception`: how people understand or view something.
- `customer perspective`: the customer's point of view.
- `perceptive teacher`: a teacher who notices details.
- `persuasive presentation`: a presentation that convinces people.
- `permanent mark`: a mark that does not wash off.
- `non-essential feature`: nice but not necessary.
- `non-urgent issue`: not needing immediate action.

## 3. Quick Generation Skill

Goal: make Quick quizzes useful for real reading, work, and daily life.

Question contexts should lean toward:

- Work: meetings, managers, teams, reports, customers, deadlines, hiring,
  feedback, presentations, investors, payroll, policy, data, budgets.
- Product/tech: apps, features, servers, user feedback, security updates,
  dashboards, releases, bugs, performance, support tickets.
- Daily life: sleep, health, cooking, money, family, travel, appointments,
  habits, housing, clothes, routines.
- Reading/outwork: symptoms, boredom tolerance, monotonous tasks, stimulation,
  quitting or tapping out.

Generation rules:

- Recovery questions come early.
- Prefer natural sentences over artificial textbook sentences.
- Use close distractors from the learner's real mistake history.
- Use current-unit words in realistic work/life contexts.
- Include some cooldown words, but do not let them dominate Recovery.
- Do not overuse one context lane in the same quiz.
- Avoid obscure trivia, overly formal scenarios, and trick questions where more
  than one option could reasonably fit.

## 4. Feedback Skill

Goal: make grading useful as review material.

For each wrong, unanswered, or unresolved item, show:

- The original question sentence.
- The learner's answer.
- The correct answer.
- Why the learner's answer is wrong in that context.
- A corrected memory sentence or phrase.

Do not only list wrong answers. The explanation should teach the contrast that
caused the mistake.

## 5. Recovery Design Skill

Goal: make Recovery targeted instead of repetitive.

Recovery should identify the failure type:

- Meaning contrast: `outbreak` vs `outburst`
- Word-family role: `perception` vs `perceptive`
- Adjective function: `perceptive` vs `persuasive`
- Context mismatch: `non-essential` vs `non-urgent`
- Collocation error: `illegible handwriting`, not `illiterate handwriting`

When creating the next quiz, convert each failure type into one clean context
question. If the learner gets it correct with confidence, lower priority
gradually. If the learner gets it wrong or uncertain, keep it in Recovery.

## 6. Source-of-Truth Boundary

This skill file controls learning style and quiz design. It does not define the
active vocabulary bank.

For vocabulary content, always use:

- `VOCABULARY_STATE.csv`
- latest `WORD_FORMATION_ADDENDUM_*.md`
- latest `RECOVERY_PRIORITIES_*.md`
- `ROTATION_STATE.md`
- recent quiz history

If a word appears only in `PROJECT_SKILLS.md` and not in the vocabulary state,
do not treat it as active vocabulary unless the user explicitly asks to add it.
