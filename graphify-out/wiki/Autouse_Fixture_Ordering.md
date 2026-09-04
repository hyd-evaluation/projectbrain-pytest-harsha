# Autouse Fixture Ordering

> 52 nodes · cohesion 0.04

## Key Concepts

- **fixture()** (182 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/fixtures.py`
- **test_fixtures_order_autouse_temp_effects.py** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/doc/en/example/fixtures/test_fixtures_order_autouse_temp_effects.py`
- **TestClassWithAutouse** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/doc/en/example/fixtures/test_fixtures_order_autouse_temp_effects.py`
- **doctest_namespace()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/doctest.py`
- **test_getfixturevalue_dynamic.py** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/test_getfixturevalue_dynamic.py`
- **ns_param()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_pathlib.py`
- **arg2()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_conftest_funcargs_only_available_in_subdir/sub2/conftest.py`
- **test_detect_recursive_dependency_error.py** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_detect_recursive_dependency_error.py`
- **test_funcarg_basic.py** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_funcarg_basic.py`
- **FixtureFunction** (2 connections)
- **c1()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/doc/en/example/fixtures/test_fixtures_order_autouse_temp_effects.py`
- **c2()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/doc/en/example/fixtures/test_fixtures_order_autouse_temp_effects.py`
- **order()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/doc/en/example/fixtures/test_fixtures_order_autouse_temp_effects.py`
- **.c3()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/doc/en/example/fixtures/test_fixtures_order_autouse_temp_effects.py`
- **arg1()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_conftest_funcargs_only_available_in_subdir/sub1/conftest.py`
- **sub2/conftest.py** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_conftest_funcargs_only_available_in_subdir/sub2/conftest.py`
- **fix1()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_detect_recursive_dependency_error.py`
- **fix2()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_detect_recursive_dependency_error.py`
- **spam()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_conftest/conftest.py`
- **spam()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_conftest/pkg/conftest.py`
- **spam()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_module/conftest.py`
- **test_extend_fixture_conftest_module.py** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_module/test_extend_fixture_conftest_module.py`
- **spam()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_module/test_extend_fixture_conftest_module.py`
- **other()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_funcarg_basic.py`
- **some()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_funcarg_basic.py`
- *... and 27 more nodes in this community*

## Relationships

- [Cache Configuration](Cache_Configuration.md) (16 shared connections)
- [Fixture Capture](Fixture_Capture.md) (15 shared connections)
- [Testing Fixtures](Testing_Fixtures.md) (9 shared connections)
- [Autouse Fixture Order](Autouse_Fixture_Order.md) (8 shared connections)
- [Fixture Dependency Order](Fixture_Dependency_Order.md) (8 shared connections)
- [Fixture Scope Order](Fixture_Scope_Order.md) (6 shared connections)
- [Terminal Reporting Tests](Terminal_Reporting_Tests.md) (5 shared connections)
- [Multi Scope Autouse](Multi_Scope_Autouse.md) (4 shared connections)
- [Fixture Scope Ordering](Fixture_Scope_Ordering.md) (4 shared connections)
- [Debugging Configuration](Debugging_Configuration.md) (4 shared connections)
- [Capture Fixture Internals](Capture_Fixture_Internals.md) (3 shared connections)
- [Legacy Path Fixtures](Legacy_Path_Fixtures.md) (3 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/doc/en/example/fixtures/test_fixtures_order_autouse_temp_effects.py`
- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/doctest.py`
- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/fixtures.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_conftest_funcargs_only_available_in_subdir/sub1/conftest.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_conftest_funcargs_only_available_in_subdir/sub2/conftest.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_detect_recursive_dependency_error.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_conftest/conftest.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_conftest/pkg/conftest.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_module/conftest.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_extend_fixture_conftest_module/test_extend_fixture_conftest_module.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_funcarg_basic.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/fill_fixtures/test_funcarg_lookupfails.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/test_fixture_named_request.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/fixtures/test_getfixturevalue_dynamic.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_debugging.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_pathlib.py`

## Audit Trail

- EXTRACTED: 224 (100%)
- INFERRED: 1 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*