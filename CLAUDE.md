# CLAUDE.md

## Status: empty repository

This repository (`sirinx-godmode`, remote `ton36475-lgtm/sirinx-godmode`) currently
contains **no files and no commits**. As of this writing:

- The working tree has nothing in it besides `.git/` — no source code, no
  `package.json`/`pyproject.toml`/`go.mod`/etc., no README, no `AGENTS.md`.
- The remote has zero refs: no default branch, no other branches, no history.
  (`git ls-remote origin` returns nothing; the remote's advertised HEAD branch
  is unresolved.)
- There is therefore no tech stack, build system, test suite, lint config,
  CI workflow, or architectural pattern to document yet — none of that exists
  in this repo.

Do not assume this repo shares structure, conventions, or tooling with other
`sirinx-*` repositories on this machine (e.g. `sirinx-solar-energy`,
`sirinx-os`, `sirinx-app`). It has not been shown to be related to them, and
nothing here should be inferred from those projects. If it turns out to be
scaffolding for one of them, update this file once actual code lands.

## For the next contributor / AI assistant

There is nothing to build, run, or test yet. Before adding code:

1. Confirm with the human what this project is actually meant to be —
   the name gives no reliable signal.
2. Once a language/framework is chosen and real files exist, replace this
   file with a proper CLAUDE.md covering: project purpose, directory layout,
   setup/dev/build/test/lint commands (sourced from actual `package.json`
   scripts, a `Makefile`, or `.github/workflows/`), and real architectural
   conventions observed in the code — not generic boilerplate.
3. Keep this note (or a short "repo bootstrapped on <date>" line) until the
   first real commit lands, so future sessions don't waste time searching
   for nonexistent config files.
