# Config

> God node · 252 connections · `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/config/__init__.py`

**Community:** [Config Help](Config_Help.md)

## Connections by Relation

### calls
- mock_config() `EXTRACTED`
- get_config() `EXTRACTED`

### contains
- config/__init__.py `EXTRACTED`
- InvocationParams `EXTRACTED`
- ArgsSource `EXTRACTED`

### imports
- _pytest/fixtures.py `EXTRACTED`
- pytester.py `EXTRACTED`
- pytest/__init__.py `EXTRACTED`
- python.py `EXTRACTED`
- hookspec.py `EXTRACTED`
- nodes.py `EXTRACTED`
- doctest.py `EXTRACTED`
- terminal.py `EXTRACTED`
- reports.py `EXTRACTED`
- runner.py `EXTRACTED`
- main.py `EXTRACTED`
- capture.py `EXTRACTED`
- legacypath.py `EXTRACTED`
- subtests.py `EXTRACTED`
- structures.py `EXTRACTED`
- warnings.py `EXTRACTED`
- logging.py `EXTRACTED`
- rewrite.py `EXTRACTED`
- tmpdir.py `EXTRACTED`
- cacheprovider.py `EXTRACTED`

### method
- .getini() `EXTRACTED`
- .parse() `EXTRACTED`
- .issue_config_time_warning() `EXTRACTED`
- ._getini_value() `EXTRACTED`
- .fromdictargs() `EXTRACTED`
- ._add_verbosity_ini() `EXTRACTED`
- ._catch_configured_warnings() `EXTRACTED`
- ._decide_args() `EXTRACTED`
- .__init__() `EXTRACTED`
- ._warn_or_fail_if_strict() `EXTRACTED`
- ._getini_ini() `EXTRACTED`
- .getoption() `EXTRACTED`
- ._consider_importhook() `EXTRACTED`
- ._mark_plugins_for_rewrite() `EXTRACTED`
- ._iter_registered_markers() `EXTRACTED`
- ._getini_toml() `EXTRACTED`
- .get_verbosity() `EXTRACTED`
- ._warn_about_missing_assertion() `EXTRACTED`
- .add_cleanup() `EXTRACTED`
- .pytest_cmdline_parse() `EXTRACTED`

### rationale_for
- Access to configuration values, pluginmanager and plugin hooks. :param… `EXTRACTED`

### references
- [fixture()](fixture.md) `EXTRACTED`
- pytest_load_initial_conftests() `EXTRACTED`
- .__init__() `EXTRACTED`
- .__init__() `EXTRACTED`
- ._register_fixture() `EXTRACTED`
- wrap_session() `EXTRACTED`
- .for_config() `EXTRACTED`
- .__init__() `EXTRACTED`
- _rewrite_test() `EXTRACTED`
- _validate_marker_names() `EXTRACTED`
- importtestmodule() `EXTRACTED`
- catch_warnings_for_item() `EXTRACTED`
- create_terminal_writer() `EXTRACTED`
- get_empty_parameterset_mark() `EXTRACTED`
- .getnode() `EXTRACTED`
- _get_line_with_reprcrash_message() `EXTRACTED`
- register_fixture() `EXTRACTED`
- pytest_assertrepr_compare() `EXTRACTED`
- _get_truncation_parameters() `EXTRACTED`
- show_fixtures_per_test() `EXTRACTED`

### uses
- [TerminalReporter](TerminalReporter.md) `INFERRED`
- Parser `INFERRED`
- UsageError `INFERRED`
- Cache `INFERRED`
- AssertionRewritingHook `INFERRED`
- Stash `INFERRED`
- Argument `INFERRED`
- PytestConfigWarning `INFERRED`
- PrintHelp `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*