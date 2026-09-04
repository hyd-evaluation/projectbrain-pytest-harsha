# Pytester Configuration

> 25 nodes · cohesion 0.12

## Key Concepts

- **PathLike** (18 connections)
- **.runpytest_inprocess()** (10 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.getnode()** (9 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.getpathnode()** (9 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.runpytest()** (9 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.from_config()** (8 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/main.py`
- **.runpytest_subprocess()** (8 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.getitems()** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.getmodulecol()** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.parseconfig()** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.parseconfigure()** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.getitem()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **._ensure_basetemp()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **.syspathinsert()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Return the collection node of a file. This is like :py:meth:`getnode` but uses…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Return result of running pytest in-process, providing a similar interface to…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Run pytest inline or in a subprocess, depending on the command line option "--…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Return a new pytest :class:`pytest.Config` instance from given commandline…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Return a new pytest configured Config instance. Returns a new…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Return the test item for a test function. Writes the source to a python file…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Return all test items collected from the module. Writes the source to a Python…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Return the module collection node for ``source``. Writes ``source`` to a file…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Run pytest as a subprocess with given arguments. Any plugins added to the…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Prepend a directory to sys.path, defaults to :attr:`path`. This is undone…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`
- **Get the collection node of a file. :param config: A pytest config. See…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`

## Relationships

- [Pytester Utilities](Pytester_Utilities.md) (15 shared connections)
- [Command Line Session](Command_Line_Session.md) (6 shared connections)
- [Mark Decorators](Mark_Decorators.md) (6 shared connections)
- [Subprocess Execution](Subprocess_Execution.md) (6 shared connections)
- [Item Fixture Ordering](Item_Fixture_Ordering.md) (5 shared connections)
- [Config Help](Config_Help.md) (4 shared connections)
- [Pytester Run Methods](Pytester_Run_Methods.md) (4 shared connections)
- [Function Parametrization Tests](Function_Parametrization_Tests.md) (1 shared connections)
- [Session Collection Tests](Session_Collection_Tests.md) (1 shared connections)
- [Plugin Manager Tests](Plugin_Manager_Tests.md) (1 shared connections)
- [Capture Manager](Capture_Manager.md) (1 shared connections)
- [Numbered Temp Directories](Numbered_Temp_Directories.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/main.py`
- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pytester.py`

## Audit Trail

- EXTRACTED: 86 (98%)
- INFERRED: 2 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*