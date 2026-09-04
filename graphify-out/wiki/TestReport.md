# TestReport

> God node · 85 connections · `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/reports.py`

**Community:** [Exception Reporting](Exception_Reporting.md)

## Connections by Relation

### contains
- reports.py `EXTRACTED`

### imports
- pytester.py `EXTRACTED`
- pytest/__init__.py `EXTRACTED`
- hookspec.py `EXTRACTED`
- terminal.py `EXTRACTED`
- runner.py `EXTRACTED`
- main.py `EXTRACTED`
- subtests.py `EXTRACTED`
- tmpdir.py `EXTRACTED`
- cacheprovider.py `EXTRACTED`
- junitxml.py `EXTRACTED`
- skipping.py `EXTRACTED`
- stepwise.py `EXTRACTED`
- pytester_assertions.py `EXTRACTED`

### inherits
- BaseReport `EXTRACTED`
- SubtestReport `EXTRACTED`

### method
- .from_item_and_call() `EXTRACTED`
- .__init__() `EXTRACTED`
- .__repr__() `EXTRACTED`

### rationale_for
- Basic test report object (also used for setup and teardown calls if they fail).… `EXTRACTED`

### references
- .pytest_runtest_logreport() `EXTRACTED`
- ._new() `EXTRACTED`
- .getreports() `EXTRACTED`
- .node_reporter() `EXTRACTED`
- .listoutcomes() `EXTRACTED`
- ._opentestcase() `EXTRACTED`
- .pytest_runtest_logreport() `EXTRACTED`
- .getfailures() `EXTRACTED`
- .update_testcase_duration() `EXTRACTED`
- .append_skipped() `EXTRACTED`
- .write_captured_output() `EXTRACTED`
- ._write_content() `EXTRACTED`
- .matchreport() `EXTRACTED`
- ._get_teardown_reports() `EXTRACTED`
- .finalize() `EXTRACTED`
- .append_error() `EXTRACTED`
- .append_failure() `EXTRACTED`
- .record_testreport() `EXTRACTED`
- .pytest_runtest_logreport() `EXTRACTED`
- pytest_report_to_serializable() `EXTRACTED`

### uses
- [Item](Item.md) `INFERRED`
- [TerminalReporter](TerminalReporter.md) `INFERRED`
- [Session](Session.md) `INFERRED`
- [ExceptionInfo](ExceptionInfo.md) `INFERRED`
- TerminalRepr `INFERRED`
- TestPython `INFERRED`
- HookRecorder `INFERRED`
- CallInfo `INFERRED`
- LogXML `INFERRED`
- _NodeReporter `INFERRED`
- TestReportSerialization `INFERRED`
- LFPlugin `INFERRED`
- TerminalProgressPlugin `INFERRED`
- TestTerminalProgressPlugin `INFERRED`
- runtestprotocol() `INFERRED`
- StepwisePlugin `INFERRED`
- pytest_exception_interact() `INFERRED`
- pytest_report_teststatus() `INFERRED`
- pytest_report_to_serializable() `INFERRED`
- pytest_report_from_serializable() `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*