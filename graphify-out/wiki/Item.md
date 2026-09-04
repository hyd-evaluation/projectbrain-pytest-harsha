# Item

> God node · 138 connections · `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/nodes.py`

**Community:** [Item Fixture Ordering](Item_Fixture_Ordering.md)

## Connections by Relation

### contains
- nodes.py `EXTRACTED`

### imports
- pytester.py `EXTRACTED`
- pytest/__init__.py `EXTRACTED`
- hookspec.py `EXTRACTED`
- doctest.py `EXTRACTED`
- terminal.py `EXTRACTED`
- reports.py `EXTRACTED`
- runner.py `EXTRACTED`
- unittest.py `EXTRACTED`
- capture.py `EXTRACTED`
- legacypath.py `EXTRACTED`
- warnings.py `EXTRACTED`
- tmpdir.py `EXTRACTED`
- mark/__init__.py `EXTRACTED`
- skipping.py `EXTRACTED`
- assertion/__init__.py `EXTRACTED`
- unraisableexception.py `EXTRACTED`
- threadexception.py `EXTRACTED`
- faulthandler.py `EXTRACTED`

### inherits
- Node `EXTRACTED`
- DoctestItem `EXTRACTED`

### method
- .__init__() `EXTRACTED`
- .location() `EXTRACTED`
- .reportinfo() `EXTRACTED`
- ._check_item_and_collector_diamond_inheritance() `EXTRACTED`
- .runtest() `EXTRACTED`
- .add_report_section() `EXTRACTED`

### rationale_for
- Base class of all test invocation items. Note that for a single function there… `EXTRACTED`

### references
- get_param_argkeys() `EXTRACTED`
- .collect() `EXTRACTED`
- pytest_pycollect_makeitem() `EXTRACTED`
- .item_capture() `EXTRACTED`
- .getfixtureinfo() `EXTRACTED`
- .perform_collect() `EXTRACTED`
- .getnode() `EXTRACTED`
- .getpathnode() `EXTRACTED`
- reorder_items_atscope() `EXTRACTED`
- .collect() `EXTRACTED`
- .get_reported_items() `EXTRACTED`
- reorder_items() `EXTRACTED`
- .getitems() `EXTRACTED`
- ._runtest_for() `EXTRACTED`
- .from_item_and_call() `EXTRACTED`
- .collect() `EXTRACTED`
- .__init__() `EXTRACTED`
- get_scope_package() `EXTRACTED`
- .getitem() `EXTRACTED`
- .collect() `EXTRACTED`

### uses
- [TerminalReporter](TerminalReporter.md) `INFERRED`
- [Session](Session.md) `INFERRED`
- [TestReport](TestReport.md) `INFERRED`
- Testdir `INFERRED`
- CollectReport `INFERRED`
- CaptureManager `INFERRED`
- PytestWarning `INFERRED`
- evaluate_skip_marks() `INFERRED`
- TestSession `INFERRED`
- SetupState `INFERRED`
- runtestprotocol() `INFERRED`
- pytest_make_collect_report() `INFERRED`
- UnitTestCase `INFERRED`
- catch_warnings_for_item() `INFERRED`
- pytest_exception_interact() `INFERRED`
- evaluate_condition() `INFERRED`
- evaluate_xfail_marks() `INFERRED`
- pytest_pycollect_makeitem() `INFERRED`
- deselect_by_mark() `INFERRED`
- call_and_report() `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*