# ExceptionInfo

> God node · 90 connections · `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/_code/code.py`

**Community:** [Exception Reporting](Exception_Reporting.md)

## Connections by Relation

### calls
- .addSubTest() `EXTRACTED`

### contains
- code.py `EXTRACTED`

### imports
- config/__init__.py `EXTRACTED`
- pytest/__init__.py `EXTRACTED`
- python.py `EXTRACTED`
- hookspec.py `EXTRACTED`
- nodes.py `EXTRACTED`
- doctest.py `EXTRACTED`
- terminal.py `EXTRACTED`
- reports.py `EXTRACTED`
- runner.py `EXTRACTED`
- unittest.py `EXTRACTED`
- subtests.py `EXTRACTED`
- _code/__init__.py `EXTRACTED`
- debugging.py `EXTRACTED`
- _pytest/raises.py `EXTRACTED`

### method
- .from_current() `EXTRACTED`
- .getrepr() `EXTRACTED`
- ._group_contains() `EXTRACTED`
- .from_exception() `EXTRACTED`
- .from_exc_info() `EXTRACTED`
- .__init__() `EXTRACTED`
- .for_later() `EXTRACTED`
- .value() `EXTRACTED`
- .fill_unfilled() `EXTRACTED`
- ._getreprcrash() `EXTRACTED`
- .match() `EXTRACTED`
- .tb() `EXTRACTED`
- .traceback() `EXTRACTED`
- .exconly() `EXTRACTED`
- .errisinstance() `EXTRACTED`
- .type() `EXTRACTED`
- .typename() `EXTRACTED`
- .__repr__() `EXTRACTED`

### rationale_for
- Wraps sys.exc_info() objects and offers help for navigating the traceback. `EXTRACTED`

### references
- raises() `EXTRACTED`
- .repr_traceback_entry() `EXTRACTED`
- .get_source() `EXTRACTED`
- .repr_failure() `EXTRACTED`
- ._repr_failure_py() `EXTRACTED`
- ._render_output() `EXTRACTED`
- .repr_excinfo() `EXTRACTED`
- .repr_traceback() `EXTRACTED`
- filter_excinfo_traceback() `EXTRACTED`
- _enter_pdb() `EXTRACTED`
- .__enter__() `EXTRACTED`
- .repr_failure() `EXTRACTED`
- test_parametrizing_conditional_raisesgroup() `EXTRACTED`
- _postmortem_exc_or_tb() `EXTRACTED`
- .repr_failure() `EXTRACTED`
- ._traceback_filter() `EXTRACTED`
- .__init__() `EXTRACTED`
- .get_exconly() `EXTRACTED`
- .filter() `EXTRACTED`
- .pytest_internalerror() `EXTRACTED`

### uses
- [TestReport](TestReport.md) `INFERRED`
- Collector `INFERRED`
- Node `INFERRED`
- CollectReport `INFERRED`
- Function `INFERRED`
- TestExceptionInfoFormatter `INFERRED`
- BaseReport `INFERRED`
- CallInfo `INFERRED`
- DoctestItem `INFERRED`
- TestTraceback_f_g_h `INFERRED`
- importtestmodule() `INFERRED`
- _format_exception_group_all_skipped_longrepr() `INFERRED`
- _format_failed_longrepr() `INFERRED`
- pytest_internalerror() `INFERRED`
- pytest_keyboard_interrupt() `INFERRED`
- test_repr_traceback_with_unicode() `INFERRED`
- test_excinfo_getstatement() `INFERRED`
- test_codepath_Queue_example() `INFERRED`
- test_entrysource_Queue_example() `INFERRED`
- test_excinfo_for_later() `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*