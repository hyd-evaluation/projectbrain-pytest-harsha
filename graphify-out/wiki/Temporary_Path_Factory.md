# Temporary Path Factory

> 40 nodes · cohesion 0.07

## Key Concepts

- **TempPathFactory** (30 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **.getbasetemp()** (9 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **.from_config()** (8 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **MonkeyPatch** (8 connections)
- **tmp_path()** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **FakeConfig** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **get_user()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **.mktemp()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **test_tmp_path_factory_create_directory_with_safe_permissions()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_factory_doesnt_follow_symlinks()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_factory_fixes_up_world_readable_permissions()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_chmod_rwx_returns_false_when_chmod_fails()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_on_rm_rf_error_os_open_unlink_fails()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **_mk_tmp()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **Path** (5 connections)
- **test_get_user_handles_getpass_oserror()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_tmppath_relative_basetemp_absolute()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.__init__()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **_raise_oserror()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **TestTmpPathHandler** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_mktemp()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **._ensure_relative_to_basetemp()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- **test_tmp_path_factory_handles_invalid_dir_characters()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.trace()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **Create a new temporary directory managed by the factory. :param basename:…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- *... and 15 more nodes in this community*

## Relationships

- [Cache Configuration](Cache_Configuration.md) (10 shared connections)
- [Directory Removal Utilities](Directory_Removal_Utilities.md) (9 shared connections)
- [Temporary Path Tests](Temporary_Path_Tests.md) (9 shared connections)
- [Numbered Temp Directories](Numbered_Temp_Directories.md) (8 shared connections)
- [Fixture Capture](Fixture_Capture.md) (4 shared connections)
- [Legacy Path Fixtures](Legacy_Path_Fixtures.md) (2 shared connections)
- [Pytester Utilities](Pytester_Utilities.md) (2 shared connections)
- [Cache API Tests](Cache_API_Tests.md) (2 shared connections)
- [Conftest Initialization](Conftest_Initialization.md) (2 shared connections)
- [Module Import Paths](Module_Import_Paths.md) (2 shared connections)
- [Config Help](Config_Help.md) (2 shared connections)
- [Legacy Path Compatibility](Legacy_Path_Compatibility.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/tmpdir.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`

## Audit Trail

- EXTRACTED: 100 (88%)
- INFERRED: 14 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*