# Progress

## Current Task
Preparing the repository state for the next session after final polishing and Tutorial Week 9 retitling.

## Working Pattern
- Inspect file
- Make minimal edits
- Review with `git diff`
- Commit small changes
- Sync using `git pull` then `git push`

## Completed
- Fixed README reference to `make_students.sh`
- Updated Exercise 4(d) in `_questions/question_04.qmd` to use `lag()` consistently across prompt, teaching guide, and solution.
- Standardised question, solution, and teaching-guide formatting across `_questions/question_01.qmd` to `_questions/question_06.qmd`.
- Corrected minor typos and wording issues in the introduction and question files without changing content or sequence.
- Tightened code scaffolds and prompt wording in Exercises 2 to 4 so they align more closely with the worked solutions.
- Drafted four in-class check question sets in `in_class_check_questions/`, then rebalanced option order so correct answers are evenly distributed across A to D.
- Added `.DS_Store` to `.gitignore` and noted that filesystem discard commands should be reported explicitly when used.
- Downloaded the Chapter 9 lecture notes on causal analytics into `lecture_notes/causal_analytics.html`.
- Reviewed the causal analytics lecture notes and mapped their coverage against the tutorial.
- Reviewed the prerequisite chapters on data wrangling and shaping/combining data.
- Assessed tutorial readiness given the lecture notes and prerequisite readings; concluded that students are broadly prepared, with implementation-level gaps that can be bridged in class by teaching assistants.
- Reviewed the rendered tutorial questions, solutions, and teaching guide.
- Corrected minor typos, punctuation, grammar, and Markdown formatting issues in the learning goals and Exercises 1, 2, 4, 5, and 6.
- Confirmed Exercise 3 is now classified as a prepare exercise, matching its placement in the rendered tutorial.
- Re-rendered the tutorial questions, solutions, and teaching guide successfully.
- Committed and pushed the final polish pass as `79a6d54` (`Polish Tutorial 10 materials`).
- Retitled the main tutorial profile to `Tutorial Week 9: Causal Analytics & Improving User Sign Up Experiences`.
- Updated the main rendered output filenames to `tutorial-week9-questions`, `tutorial-week9-solutions`, and `tutorial-week9-teaching-guide`.
- Left the in-class check question titles as `Tutorial 10 In-Class Check` for now, as agreed.
- Confirmed the latest commit is `b0fad4b` (`Retitle to reflect updated sequencing for this semester`), and the worktree was clean before this state-file update.

## Known Notes
- `make_students.sh` uses `grep -P`, which fails on macOS/BSD `grep`; the script still creates `tutorial_student.qmd`, but emits portability warnings/errors.
- `tutorial_student.qmd`, rendered HTML outputs, lecture notes HTML, and in-class check HTML files are ignored/generated artifacts.
- The main source of truth for visible tutorial title and output filenames is the Quarto profile files (`_quarto-r-questions.yml`, `_quarto-r-solutions.yml`, `_quarto-r-teaching-guide.yml`).

## Next Step
- Start by reading `README.md`, `CONSTRAINTS.md`, `AGENT_INSTRUCTIONS.md`, and this `PROGRESS.md`.
- Check `git status --short` before editing.
- Re-render the main tutorial profiles after any source edits and verify the generated files use the `tutorial-week9-*` output names.
- Review and fix the `make_students.sh` portability issue on macOS/BSD `grep`, if the student `.qmd` output is needed.
- Decide whether the in-class check question titles should remain `Tutorial 10 In-Class Check` or be retitled to Tutorial Week 9 before distribution.
- Finalize delivery materials for the teaching team: tutorial questions for textbook, revised lecture notes for textbook if applicable, Posit lecture/tutorial workspaces, and teaching guide.
