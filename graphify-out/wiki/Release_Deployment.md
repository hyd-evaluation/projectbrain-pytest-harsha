# Release Deployment

> 52 nodes · cohesion 0.05

## Key Concepts

- **build Job** (10 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **update-plugin-list Job** (9 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/update-plugin-list.yml`
- **Generate GitHub Release Notes Job** (8 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/deploy.yml`
- **actions/checkout** (8 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **Publish to PyPI Job** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/deploy.yml`
- **Release Procedure** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/RELEASING.rst`
- **Create GitHub Release Job** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/deploy.yml`
- **Package Job** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/deploy.yml`
- **Push Tag Job** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/deploy.yml`
- **deploy Workflow** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/deploy.yml`
- **./.github/actions/setup-tox** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **Doc Check Links Job** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/doc-check-links.yml`
- **Build Job** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/prepare-release-pr.yml`
- **package Job** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **actions/download-artifact** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **check Job** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **codecov/codecov-action** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **test Workflow** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **prepare-release-pr Workflow** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/RELEASING.rst`
- **hynek/build-and-inspect-python-package** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **junit.xml** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **tox run** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- **actions/cache** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/update-plugin-list.yml`
- **Find Current Maintenance Branch Step** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/update-plugin-list.yml`
- **git ls-remote** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/update-plugin-list.yml`
- *... and 27 more nodes in this community*

## Relationships

- No strong cross-community connections detected

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/deploy.yml`
- `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/doc-check-links.yml`
- `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/prepare-release-pr.yml`
- `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/test.yml`
- `raw/code/hyd-evaluation/pytest-harsha/.github/workflows/update-plugin-list.yml`
- `raw/code/hyd-evaluation/pytest-harsha/RELEASING.rst`

## Audit Trail

- EXTRACTED: 70 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*