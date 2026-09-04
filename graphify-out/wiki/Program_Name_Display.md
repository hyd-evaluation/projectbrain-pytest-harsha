# Program Name Display

> 20 nodes · cohesion 0.11

## Key Concepts

- **TestProgName** (10 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **_get_prog_name()** (6 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/config/__init__.py`
- **.test_console_main_deprecated()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **.test_get_prog_name_direct_pytest()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **.test_get_prog_name_empty_argv()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **.test_get_prog_name_python_m_pytest()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **.test_prog_in_error_message_cli()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **.test_prog_in_error_message_programmatic()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **.test_prog_in_usage_cli()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **.test_prog_in_usage_programmatic()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **Determine the CLI program name from the argument vector. :param argv: The…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/config/__init__.py`
- **Test program name display in help and error messages (issue #1764).** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **When argv[0] is a pytest entry point, prog should be 'pytest'.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **When argv[0] is __main__.py, prog should be 'python -m pytest'.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **When argv is empty, should default to 'pytest'.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **Error messages should show 'pytest.main()' when called programmatically.…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **Error messages should show 'python -m pytest' when called from CLI subprocess.…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **Usage line should show 'pytest.main()' when called programmatically.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **Usage line should show 'python -m pytest' when called from CLI subprocess.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`
- **Calling pytest.console_main() should emit a deprecation warning.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`

## Relationships

- [INI Option Tests](INI_Option_Tests.md) (4 shared connections)
- [Frame Wrapper](Frame_Wrapper.md) (1 shared connections)
- [Cache Configuration](Cache_Configuration.md) (1 shared connections)
- [Config Tests](Config_Tests.md) (1 shared connections)
- [Rootdir Config Discovery](Rootdir_Config_Discovery.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/src/_pytest/config/__init__.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_config.py`

## Audit Trail

- EXTRACTED: 29 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*