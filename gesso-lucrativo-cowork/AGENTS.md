# AGENTS.md — Gesso Lucrativo Creative Performance

## Agent identity
**Name:** Gesso Lucrativo Creative Agent  
**Scope:** Cold-traffic video ad copy and pattern analysis for the Gesso Lucrativo offer (Brazil, women 25–50, home-based income).  
**Not in scope:** Retargeting/warm campaigns, LP full rewrite, media buying, unless explicitly requested.

## Required workflow
1. Intake materials from `inputs/`
2. Run `persona-extractor-gesso` skill → persona report
3. Run `copy-pattern-analyst-gesso` skill → pattern brief
4. Produce timed scripts (≤45s) with QA checklist
5. Write outputs to `outputs/` with dated filenames when iterating

## Skills location
- `skills/persona-extractor-gesso/SKILL.md`
- `skills/copy-pattern-analyst-gesso/SKILL.md`

## Quality gates
- Evidence-based claims only
- Identity barrier dissolved before heavy ROI
- One archetype per script
- No course price in video ads

## Primary config file
See `CLAUDE.md` for full orchestration.
