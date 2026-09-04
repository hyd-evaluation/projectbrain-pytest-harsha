# Temporary Path Tests

> 30 nodes · cohesion 0.11

## Key Concepts

- **test_tmpdir.py** (32 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **Pytester** (16 connections)
- **TestConfigTmpPath** (8 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **attempt_symlink_to()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_get_user_uid_not_found()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_fallback_uid_not_found()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_basetemp_with_read_only_files()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_mktemp()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_always_is_realpath()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_fallback_tox_env()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_retention_policy_invalid()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_retention_count()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **break_getuser()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **parametrize** (2 connections)
- **usefixtures** (2 connections)
- **test_tmp_path_factory()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_fixture()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **test_tmp_path_too_long_on_parametrization()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_getbasetemp_custom_removes_old()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_policy_all_keeps_dir_when_skipped_from_fixture()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_policy_failed_removes_basedir_when_all_passed()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_policy_failed_removes_dir_when_skipped_from_fixture()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_policy_failed_removes_only_passed_dir()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **.test_policy_none_delete_all()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- **Test that tmp_path works even if environment variables required by getpass…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`
- *... and 5 more nodes in this community*

## Relationships

- [Temporary Path Factory](Temporary_Path_Factory.md) (9 shared connections)
- [Cache Configuration](Cache_Configuration.md) (5 shared connections)
- [Directory Removal Utilities](Directory_Removal_Utilities.md) (4 shared connections)
- [Numbered Temp Directories](Numbered_Temp_Directories.md) (3 shared connections)
- [Thread Exception Hook](Thread_Exception_Hook.md) (1 shared connections)
- [File Stat Wrapper](File_Stat_Wrapper.md) (1 shared connections)
- [Path Cleanup Utilities](Path_Cleanup_Utilities.md) (1 shared connections)
- [Autouse Fixture Ordering](Autouse_Fixture_Ordering.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/testing/test_tmpdir.py`

## Audit Trail

- EXTRACTED: 72 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*