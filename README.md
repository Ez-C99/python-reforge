# python-reforge

A structured Python re-learning repo built around:

1) Real Python learning paths (core spine)
2) Consolidation via *Learning Python* (Mark Lutz, 6th ed.)
3) Practice via katas + tests (portfolio trail > certificates)

## What this repo contains

- Notes that I’d actually re-read later
- Small katas that reinforce specific concepts
- Tests that prove I didn’t just “watch content”

## Study workflow (repeat for each Real Python path)

1. **Real Python first**
   - Complete the resources in the learning path (courses/tutorials/quizzes).
2. **Consolidate with Lutz**
   - Read the mapped chapters and do a handful of end-of-chapter questions.
3. **Practise**
   - Add 3–10 katas and (from intermediate onwards) add tests.

## Repo structure

```plaintext
python-reforge
├─ LICENSE
├─ README.md
├─ exercises
├─ katas
│  ├─ algorithms
│  ├─ core
│  └─ interview-prep
├─ notes
│  ├─ core-language
│  ├─ oop
│  ├─ packaging
│  └─ testing
├─ tests
└─ tooling
   ├─ .pre-commit-config.yaml
   └─ pyproject.toml
```

## Progress tracking

- [ ] Core Language: Basics
- [ ] Core Language: Intermediate
- [ ] Core Language: Advanced
- [ ] Beyond the Core: Web Scraping
- [ ] Beyond the Core: Optional paths (viz, DS, ML, etc.)
- [ ] Beyond the Core: DevOps With Python (final compulsory)

## Tooling (evolves as I learn)

- Formatter/linter: ruff (or black + ruff)
- Tests: pytest
- Types: mypy (later)
- Automation: pre-commit + CI

## How to run katas

- Create a virtualenv
- Install dev dependencies
- Run tests

(Exact commands live in `tooling/` as the setup evolves.)

## Licence

MIT
