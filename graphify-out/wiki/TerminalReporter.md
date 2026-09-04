# TerminalReporter

> God node · 121 connections · `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/terminal.py`

**Community:** [Terminal Summary](Terminal_Summary.md)

## Connections by Relation

### calls
- .test_isatty() `EXTRACTED`
- .test_rewrite() `EXTRACTED`
- pytest_configure() `EXTRACTED`
- .test_internalerror() `EXTRACTED`
- .test_show_runtest_logstart() `EXTRACTED`
- .test_writeline() `EXTRACTED`
- tr() `EXTRACTED`

### contains
- terminal.py `EXTRACTED`

### imports
- config/__init__.py `EXTRACTED`
- pytest/__init__.py `EXTRACTED`
- hookspec.py `EXTRACTED`
- runner.py `EXTRACTED`
- legacypath.py `EXTRACTED`
- warnings.py `EXTRACTED`
- logging.py `EXTRACTED`
- junitxml.py `EXTRACTED`
- helpconfig.py `EXTRACTED`
- pastebin.py `EXTRACTED`
- terminalprogress.py `EXTRACTED`

### method
- .pytest_runtest_logreport() `EXTRACTED`
- .summary_failures_combined() `EXTRACTED`
- .write_line() `EXTRACTED`
- .write_sep() `EXTRACTED`
- .pytest_terminal_summary() `EXTRACTED`
- .summary_passes_combined() `EXTRACTED`
- .pytest_sessionfinish() `EXTRACTED`
- ._get_reports_to_display() `EXTRACTED`
- ._add_stats() `EXTRACTED`
- ._write_progress_information_filling_space() `EXTRACTED`
- .pytest_sessionstart() `EXTRACTED`
- .summary_errors() `EXTRACTED`
- .summary_stats() `EXTRACTED`
- ._get_progress_information_message() `EXTRACTED`
- .report_collect() `EXTRACTED`
- ._locationline() `EXTRACTED`
- .getreports() `EXTRACTED`
- ._handle_teardown_sections() `EXTRACTED`
- ._outrep_summary() `EXTRACTED`
- ._get_main_color() `EXTRACTED`

### references
- .__init__() `EXTRACTED`
- .test_emit_progress_sequences() `EXTRACTED`
- .test_session_lifecycle() `EXTRACTED`
- .mock_tr() `EXTRACTED`
- .pytest_terminal_summary() `EXTRACTED`
- .__init__() `EXTRACTED`

### uses
- [Config](Config.md) `INFERRED`
- [Item](Item.md) `INFERRED`
- [Session](Session.md) `INFERRED`
- [TestReport](TestReport.md) `INFERRED`
- Node `INFERRED`
- CollectReport `INFERRED`
- BaseReport `INFERRED`
- LogXML `INFERRED`
- pytest_load_initial_conftests() `INFERRED`
- ExceptionRepr `INFERRED`
- TestTerminal `INFERRED`
- TestTerminalProgressPlugin `INFERRED`
- _LiveLoggingStreamHandler `INFERRED`
- test_live_logging_suspends_capture() `INFERRED`
- TerminalReporter_startdir() `INFERRED`
- pytest_terminal_summary() `INFERRED`
- pytest_terminal_summary() `INFERRED`
- showhelp() `INFERRED`
- pytest_configure() `INFERRED`
- pytest_terminal_summary() `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*