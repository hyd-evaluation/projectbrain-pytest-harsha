# PytestPluginManager

> God node · 76 connections · `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/config/__init__.py`

**Community:** [Community 66](Community_66.md)

## Connections by Relation

### calls
- get_config() `EXTRACTED`
- ConftestWithSetinitial() `EXTRACTED`
- test_setinitial_conftest_subdirs() `EXTRACTED`
- test_conftest_import_order() `EXTRACTED`
- test_conftestcutdir() `EXTRACTED`
- test_conftestcutdir_inplace_considered() `EXTRACTED`
- test_doubledash_considered() `EXTRACTED`
- test_issue151_load_all_conftests() `EXTRACTED`
- test_hookrecorder_basic() `EXTRACTED`
- .test_basic_init() `EXTRACTED`
- .test_immediate_initialization_and_incremental_are_the_same() `EXTRACTED`
- pytestpm() `EXTRACTED`
- .test_canonical_import() `EXTRACTED`
- .test_register_imported_modules() `EXTRACTED`
- test_hookimpl_via_function_attributes_are_deprecated() `INFERRED`
- test_hookspec_via_function_attributes_are_deprecated() `INFERRED`

### contains
- config/__init__.py `EXTRACTED`

### imports
- pytester.py `EXTRACTED`
- pytest/__init__.py `EXTRACTED`
- hookspec.py `EXTRACTED`
- main.py `EXTRACTED`
- legacypath.py `EXTRACTED`
- debugging.py `EXTRACTED`

### inherits
- PluginManager `EXTRACTED`

### method
- ._importconftest() `EXTRACTED`
- .register() `EXTRACTED`
- ._set_initial_conftests() `EXTRACTED`
- ._loadconftestmodules() `EXTRACTED`
- .__init__() `EXTRACTED`
- ._import_plugin_specs() `EXTRACTED`
- ._getconftestmodules() `EXTRACTED`
- ._rget_with_confmod() `EXTRACTED`
- .import_plugin() `EXTRACTED`
- .parse_hookimpl_opts() `EXTRACTED`
- ._is_in_confcutdir() `EXTRACTED`
- ._check_non_top_pytest_plugins() `EXTRACTED`
- .consider_pluginarg() `EXTRACTED`
- .consider_conftest() `EXTRACTED`
- .consider_module() `EXTRACTED`
- .parse_hookspec_opts() `EXTRACTED`
- .hasplugin() `EXTRACTED`
- .pytest_configure() `EXTRACTED`
- .consider_preparse() `EXTRACTED`
- .consider_env() `EXTRACTED`

### rationale_for
- A :py:class:`pluggy.PluginManager <pluggy.PluginManager>` with additional… `EXTRACTED`

### references
- conftest_setinitial() `EXTRACTED`
- .__init__() `EXTRACTED`
- pytest_addoption() `EXTRACTED`
- pytest_cmdline_parse() `EXTRACTED`
- pytest_plugin_registered() `EXTRACTED`
- .pytest_cmdline_parse() `EXTRACTED`
- pytest_addhooks() `EXTRACTED`
- pytest_plugin_registered() `EXTRACTED`
- .make_hook_recorder() `EXTRACTED`
- test_importplugin_error_message() `EXTRACTED`
- .test_consider_conftest_deps() `EXTRACTED`
- .test_consider_env_entry_point_name() `EXTRACTED`
- .test_consider_env_plugin_instantiation() `EXTRACTED`
- .test_consider_module_entry_point_name() `EXTRACTED`
- get_plugin_manager() `EXTRACTED`
- .__init__() `EXTRACTED`
- .__init__() `EXTRACTED`
- .test_consider_env_fails_to_import() `EXTRACTED`
- .test_consider_module() `EXTRACTED`
- .test_import_plugin_dotted_name() `EXTRACTED`

### uses
- UsageError `INFERRED`
- PytestConfigWarning `INFERRED`
- ImportMode `INFERRED`
- Skipped `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*