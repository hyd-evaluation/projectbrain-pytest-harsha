# Capture Fixture Internals

> 20 nodes · cohesion 0.10

## Key Concepts

- **CaptureFixture** (24 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **capfd()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **capsysbinary()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **capteesys()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **test_stderr_write_returns_len()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_capture.py`
- **.disabled()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **._is_started()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **._resume()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **._start()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **._suspend()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **.close()** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **Temporarily disable capturing while inside the ``with`` block.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **r"""Enable simultaneous text capturing and pass-through of writes to…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **r"""Enable bytes capturing of writes to ``sys.stdout`` and ``sys.stderr``. The…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **r"""Enable text capturing of writes to file descriptors ``1`` and ``2``. The…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **Object returned by the :fixture:`capsys`, :fixture:`capsysbinary`,…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **Suspend this fixture's own capturing temporarily.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **Resume this fixture's own capturing temporarily.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **Whether actively capturing -- not disabled or closed.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- **Write on Encoded files, namely captured stderr, should return number of…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_capture.py`

## Relationships

- [Cache Configuration](Cache_Configuration.md) (6 shared connections)
- [Fixture Capture](Fixture_Capture.md) (6 shared connections)
- [Capture Tests](Capture_Tests.md) (4 shared connections)
- [Autouse Fixture Ordering](Autouse_Fixture_Ordering.md) (3 shared connections)
- [Capture IO](Capture_IO.md) (2 shared connections)
- [Capture Base Classes](Capture_Base_Classes.md) (1 shared connections)
- [Subtests Support](Subtests_Support.md) (1 shared connections)
- [Capture Manager](Capture_Manager.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/capture.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_capture.py`

## Audit Trail

- EXTRACTED: 34 (79%)
- INFERRED: 9 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*