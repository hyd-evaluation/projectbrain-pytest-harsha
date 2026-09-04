# Numbered Temp Directories

> 23 nodes · cohesion 0.14

## Key Concepts

- **Path** (19 connections)
- **make_numbered_dir()** (15 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **create_cleanup_lock()** (10 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **maybe_delete_a_numbered_dir()** (10 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **TestNumberedDir** (10 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **._do_cleanup()** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **get_lock_path()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **test_access_denied_during_cleanup()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_pathlib.py`
- **test_suppress_error_removing_lock()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_pathlib.py`
- **.test_lock_register_cleanup_removal()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_removal_accepts_lock()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_cleanup_ignores_symlink()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_cleanup_keep_0()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_cleanup_locked()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_make()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_cleanup_keep()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_cleanup_lock_create()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **_AnyPurePath** (1 connections)
- **Create a directory with an increased number as suffix for the given prefix.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **Create a lock to prevent premature directory cleanup.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **Remove a numbered directory if its lock can be obtained and it does not seem to…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- **Ensure that deleting a numbered dir does not fail because of OSErrors (#4262).** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_pathlib.py`
- **ensure_deletable should be resilient if lock file cannot be removed (#5456,…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_pathlib.py`

## Relationships

- [Path Cleanup Utilities](Path_Cleanup_Utilities.md) (18 shared connections)
- [Directory Removal Utilities](Directory_Removal_Utilities.md) (9 shared connections)
- [Temporary Path Factory](Temporary_Path_Factory.md) (8 shared connections)
- [Package Path Resolution](Package_Path_Resolution.md) (4 shared connections)
- [Temporary Path Tests](Temporary_Path_Tests.md) (3 shared connections)
- [Cache Configuration](Cache_Configuration.md) (2 shared connections)
- [Module Import Paths](Module_Import_Paths.md) (2 shared connections)
- [Pytester Configuration](Pytester_Configuration.md) (1 shared connections)
- [Assertion Pass Hook](Assertion_Pass_Hook.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/pathlib.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_pathlib.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`

## Audit Trail

- EXTRACTED: 82 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*