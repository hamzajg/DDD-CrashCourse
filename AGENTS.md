# AGENTS.md — DDD-CrashCourse

Guidance for AI agents (and humans) working in this repository.

## Project

An article series introducing **strategic Domain-Driven Design** — the
part before aggregates/entities/repositories: what a domain is, how to
split it into subdomains, how to classify and prioritise them. Based on
Eric Evans' *DDD* and Vaughn Vernon's *IDDD*, in the author's own words,
with an extended EMR example.
Content: markdown chapters + one diagram. **No code, no build.**

## Commands

No build, no tests, no CI. This is a documentation-only repository.

| Task | Command |
|---|---|
| Preview chapter | open `chapter-1.md` in any markdown viewer/editor |
| Lint (optional) | any markdown linter — none configured |

## Architecture

```
DDD-CrashCourse/
  README.md          series index + chapter table
  chapter-1.md       Strategic DDD: domain concept, core/supporting/
                     generic subdomains, EMR classification,
                     problems→solutions
  ch-1-subdomains.png  diagram referenced by chapter 1
  LICENSE
```

One chapter so far; more chapters get `chapter-N.md` + README table rows.

## Conventions

- **Markdown only** — don't add code projects, configs, or tooling
  without a clear reason; this is a reading series.
- Chapters follow the book lineage (Evans/Vernon) but in the author's
  voice — keep the EMR example consistent across chapters.
- Diagrams as images alongside the markdown that references them.
- KISS: prose + diagrams; no static-site generator needed.

## Landmines

- **Default branch is `master`, not `main`.**
- No code — don't invent build/test commands.
- Chapter numbering is sequential — `chapter-1.md` exists; next is
  `chapter-2.md`.
- Keep the subdomain classification (core/supporting/generic) consistent
  with chapter 1 — later chapters build on it.

## Agent rules

- Branch from `master`; name branches `feat/*`, `fix/*`, `chore/*`, `docs/*`.
- Docs-only changes still go through a PR; never commit to `master` directly.
- Verify before claiming: re-read the chapter you changed; markdown
  renders correctly; links/images resolve.
- Keep changes minimal and consistent with surrounding prose. No drive-by
  rewrites.
- Update AGENTS.md / docs/ARCHITECTURE.md when chapters or structure
  change.
