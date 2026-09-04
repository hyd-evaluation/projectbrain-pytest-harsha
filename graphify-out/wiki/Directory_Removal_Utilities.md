# Directory Removal Utilities

> 35 nodes · cohesion 0.09

## Key Concepts

- **on_rm_rf_error()** (16 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **TestRmRf** (16 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **rm_rf()** (14 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **skipif** (10 connections)
- **_chmod_rwx()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **.chmod_r()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_on_rm_rf_error_chmod_retry_walks_parents()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_on_rm_rf_error_os_open_handles_directory()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_on_rm_rf_error_os_open_handles_file()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_on_rm_rf_error_os_open_parent_perms()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_get_user()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_chmod_rwx_returns_false_on_nonexistent_path()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_chmod_rwx_returns_false_when_already_sufficient()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_on_rm_rf_error()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_on_rm_rf_error_os_open_returns_false_when_chmod_ineffective()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_rm_rf_with_no_exec_permission_directories()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_rm_rf_with_read_only_directory()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_rm_rf_with_read_only_file()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_rm_rf()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **BaseException** (1 connections)
- **TracebackType** (1 connections)
- **Handle known read-only errors during rmtree. The returned value is used only by…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **Remove the path contents recursively, even if some elements are read-only.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **Grant owner sufficient permissions for deletion. Directories get ``S_IRWXU``…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **Test that get_user() function works even if environment variables required by…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- *... and 10 more nodes in this community*

## Relationships

- [Temporary Path Factory](Temporary_Path_Factory.md) (9 shared connections)
- [Numbered Temp Directories](Numbered_Temp_Directories.md) (9 shared connections)
- [Path Cleanup Utilities](Path_Cleanup_Utilities.md) (7 shared connections)
- [Cache Configuration](Cache_Configuration.md) (4 shared connections)
- [Temporary Path Tests](Temporary_Path_Tests.md) (4 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`

## Audit Trail

- EXTRACTED: 84 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*