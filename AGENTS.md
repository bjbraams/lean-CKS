# Project instructions — lean-CKS

Before working, read and follow [the shared Lean instructions](../lean-codes/AGENTS.common.md),
then apply the project-specific rules below. Resolve that path relative to this file.
Local rules take precedence over the shared defaults. If the shared file is unavailable,
report that fact rather than proceeding without it.

## Build settings

- Lake root: the directory containing this `AGENTS.md`.
- Build output: `.lake/build-CKS`; preserve the matching `buildDir` in `lakefile.toml`.
- Ordinary build command: `lake build > /tmp/cks-build.log 2>&1`.

## Project

This is a new project in the area of Core Knowledge of Statistics and Data Science at the level
of graduate students and beginning researchers. The project follows the style of the earlier
sibling ../lean-CKMA project that is devoted to core knowledge in mathematical analysis.

One component of the lean-CKS project is to assemble a bibliography. The main working file is
`CKS-bib.md`. This file is meant for the human reader. The file is divided into topical sections
numbered from 101 on.

PDF files for some of the references are (will be) in the directory ./References/. The directory
./ReferencesSuppl/ will contain PDF files for some books in the same general area that are not
in the bibliography.

There may be additional files, for example `*.json`, for precise bibliographical data.

You may be asked to edit, revise or expand any of the Markdown files in the project directory or
to create new such files.
- Keep changes narrowly related to the request.
- Preserve unrelated user changes.
- Do not commit changes unless explicitly requested.
