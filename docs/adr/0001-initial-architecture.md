# ADR 0001 — Initial architecture

Date: 2026-11-13 (baseline recorded retroactively)
Status: accepted (describes what is built)

## Context

A written series on strategic DDD — knowledge transfer, not software.

## Decisions

1. **Markdown chapters, no site generator.** `chapter-N.md` + README
   index. Rationale: KISS — readers use any markdown viewer; a static
   site adds tooling for no benefit.
2. **Strategic before tactical.** Series starts with domains/subdomains
   (Evans/Vernon strategic layer), not code patterns. Rationale: the
   author found strategic DDD is the part people skip — and the part
   that matters most.
3. **Single extended example.** EMR system carries through chapters.
   Rationale: concrete classification beats abstract lists.
4. **Author's voice, book lineage.** Based on Evans/Vernon but
   explained originally. Rationale: add value beyond summarising.

## Consequences / open questions

- Series is early (chapter 1) — chapter order and depth will evolve;
  the README table is the index of record.
- Images are committed alongside chapters — keep them referenced
  relatively.
- If the series grows large, a TOC or per-part README may help —
  decide then, not now.
