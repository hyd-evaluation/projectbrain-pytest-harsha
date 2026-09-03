# Session

> God node · 96 connections · `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/main.py`

**Community:** [Community 4](Community_4.md)

## Connections by Relation

### contains
- main.py `EXTRACTED`

### imports
- _pytest/fixtures.py `EXTRACTED`
- pytester.py `EXTRACTED`
- pytest/__init__.py `EXTRACTED`
- python.py `EXTRACTED`
- hookspec.py `EXTRACTED`
- nodes.py `EXTRACTED`
- terminal.py `EXTRACTED`
- runner.py `EXTRACTED`
- legacypath.py `EXTRACTED`
- warnings.py `EXTRACTED`
- logging.py `EXTRACTED`
- rewrite.py `EXTRACTED`
- cacheprovider.py `EXTRACTED`
- assertion/__init__.py `EXTRACTED`
- stepwise.py `EXTRACTED`

### method
- .perform_collect() `EXTRACTED`
- .from_config() `EXTRACTED`
- .gethookproxy() `EXTRACTED`
- ._collect_one_node() `EXTRACTED`
- .genitems() `EXTRACTED`
- ._collect_path() `EXTRACTED`
- .collect() `EXTRACTED`
- .pytest_collectstart() `EXTRACTED`
- .pytest_runtest_logreport() `EXTRACTED`
- .isinitpath() `EXTRACTED`
- .__init__() `EXTRACTED`
- .shouldstop() `EXTRACTED`
- .shouldfail() `EXTRACTED`
- .startpath() `EXTRACTED`
- ._node_location_to_relpath() `EXTRACTED`
- .__repr__() `EXTRACTED`

### rationale_for
- The root of the collection tree. ``Session`` collects the initial paths given… `EXTRACTED`

### references
- wrap_session() `EXTRACTED`
- .__init__() `EXTRACTED`
- .pytest_sessionfinish() `EXTRACTED`
- show_fixtures_per_test() `EXTRACTED`
- _main() `EXTRACTED`
- .__init__() `EXTRACTED`
- .pytest_sessionstart() `EXTRACTED`
- .__init__() `EXTRACTED`
- .__init__() `EXTRACTED`
- .__init__() `EXTRACTED`
- ._flush_pending_conftests_to_session() `EXTRACTED`
- .pytest_runtestloop() `EXTRACTED`
- .pytest_collection_finish() `EXTRACTED`
- .pytest_sessionstart() `EXTRACTED`
- .session() `EXTRACTED`
- .set_session() `EXTRACTED`
- .pytest_sessionfinish() `EXTRACTED`
- pytest_collection() `EXTRACTED`
- pytest_runtestloop() `EXTRACTED`
- .pytest_sessionstart() `EXTRACTED`

### uses
- [Item](Item.md) `INFERRED`
- [TerminalReporter](TerminalReporter.md) `INFERRED`
- [TestReport](TestReport.md) `INFERRED`
- [FixtureRequest](FixtureRequest.md) `INFERRED`
- Node `INFERRED`
- CollectReport `INFERRED`
- Function `INFERRED`
- PytestWarning `INFERRED`
- FixtureManager `INFERRED`
- TestFunction `INFERRED`
- AssertionRewritingHook `INFERRED`
- LoggingPlugin `INFERRED`
- pytest_load_initial_conftests() `INFERRED`
- LFPlugin `INFERRED`
- TerminalProgressPlugin `INFERRED`
- TestSession `INFERRED`
- SetupState `INFERRED`
- get_param_argkeys() `INFERRED`
- StepwisePlugin `INFERRED`
- get_scope_node() `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*