# Assertion Import Hook

> 33 nodes · cohesion 0.09

## Key Concepts

- **AssertionRewritingHook** (27 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **AssertionState** (11 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/__init__.py`
- **install_importhook()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/__init__.py`
- **._early_rewrite_bailout()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **._should_rewrite()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **TestEarlyRewriteBailout** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertrewrite.py`
- **.find_spec()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **.mark_rewrite()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **.hook()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertrewrite.py`
- **._is_marked_for_rewrite()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **test_rewrite_infinite_recursion()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertrewrite.py`
- **.test_basic()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertrewrite.py`
- **.test_pattern_contains_subdirectories()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertrewrite.py`
- **.create_module()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **._warn_already_imported()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **ModuleType** (3 connections)
- **.__init__()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/__init__.py`
- **.get_data()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **.get_resource_reader()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **.__init__()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **.set_session()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- **ModuleSpec** (2 connections)
- **State for the assertion plugin.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/__init__.py`
- **Try to install the rewrite hook, raise SystemError if it fails.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/__init__.py`
- **A fast way to get out of rewriting modules. Profiling has shown that the call…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- *... and 8 more nodes in this community*

## Relationships

- [Assertion Rewriting](Assertion_Rewriting.md) (8 shared connections)
- [Assertion Pass Hook](Assertion_Pass_Hook.md) (6 shared connections)
- [Config Help](Config_Help.md) (5 shared connections)
- [Cache Configuration](Cache_Configuration.md) (4 shared connections)
- [Assertion Rewriting Tests](Assertion_Rewriting_Tests.md) (3 shared connections)
- [Assertion Rewrite Hooks](Assertion_Rewrite_Hooks.md) (2 shared connections)
- [Command Line Session](Command_Line_Session.md) (2 shared connections)
- [Path Utilities](Path_Utilities.md) (2 shared connections)
- [Monkeypatch Utilities](Monkeypatch_Utilities.md) (1 shared connections)
- [Command Line Arguments](Command_Line_Arguments.md) (1 shared connections)
- [Autouse Fixture Ordering](Autouse_Fixture_Ordering.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/__init__.py`
- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/assertion/rewrite.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertrewrite.py`

## Audit Trail

- EXTRACTED: 73 (91%)
- INFERRED: 7 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*