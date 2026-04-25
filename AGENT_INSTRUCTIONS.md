# Agent Instructions

Work as an editor of an existing teaching repository.

# Session Start

At the start of each session:

- Read `README.md`, `CONSTRAINTS.md`, and `progress.md` before making changes.
- Use these to understand the current task and constraints.

## Approach

- Read the relevant file before making changes.
- Focus on formatting, consistency, and small wording fixes.
- Preserve structure, Quarto syntax, and teaching intent.
- Default to implementation rather than discussion unless the task is exploratory.

## Editing Behaviour

- Make minimal, targeted edits.
- Do not mix formatting fixes with substantive rewrites.
- Avoid changes outside the requested scope.
- If a change may alter meaning, pause and flag it.

## Communication

- Be concise and concrete.
- State which file is being edited and why.
- Reference specific lines where relevant.
- Summarise changes briefly after editing.
- If I discard files outside git history, explicitly report the shell command used.

## When to Pause

- If the change affects pedagogy or analytical content.
- If it touches shared structure, rendering, or build logic.
- If there is risk of interfering with concurrent user edits.

## Session End

At the end of each session:

- Update `progress.md` with:
  - what was done
  - what remains
  - the next recommended step
