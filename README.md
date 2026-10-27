# Chicago Student Report Skill

A reusable Codex skill for creating and formatting English-language student essays, assignments, and reports using Chicago-style conventions. It prioritizes course instructions and, when written formatting notes conflict with supplied screenshots, follows the screenshots for heading hierarchy.

## What it covers

- Student-paper page setup: US Letter, 1-inch margins, readable serif type, double-spaced body, and 0.5-inch first-line indents.
- Title-page layout and page-number options, including a title page counted as page 1 with body numbering beginning at 2.
- Image-based heading hierarchy and optional numbered sections.
- Chicago Notes-Bibliography by default, with Author-Date supported when requested.
- Footnotes, bibliography, table and figure captions, optional front matter, appendices, and template placeholders.
- Editable DOCX output with rendered-page inspection when a Word document is requested.

This is a student-paper aid, not an official certification or a substitute for an instructor's assignment sheet. Chicago requirements vary by edition, discipline, and institution; local instructions take precedence.

## Install

Copy the folder skills/chicago-student-report into your Codex skills directory. The resulting path should be:

    ~/.codex/skills/chicago-student-report/SKILL.md

On Windows, if CODEX_HOME is set, use %CODEX_HOME%\skills\chicago-student-report; otherwise use %USERPROFILE%\.codex\skills\chicago-student-report. Restart or refresh Codex's skill catalog if the skill does not appear immediately.

## Use

Invoke explicitly with $chicago-student-report.

Example request:

> Use $chicago-student-report to make an English report template about [topic]. Use Chicago Notes-Bibliography, include a title page and table of contents, and preserve placeholders for my course and instructor details.

You can also request Author-Date, omit the title page, or provide course-specific formatting instructions.

## Package layout

- skills/chicago-student-report/SKILL.md — skill instructions
- skills/chicago-student-report/agents/openai.yaml — Codex UI metadata and invocation policy
- LICENSE — MIT License

## License

Released under the MIT License. See LICENSE.
