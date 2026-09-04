# Testing Fixtures

> 23 nodes · cohesion 0.10

## Key Concepts

- **testing/conftest.py** (12 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **mock_timing()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **MonkeyPatch** (5 connections)
- **remove_ci_env_var()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **dummy_yaml_custom_test()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **reset_colors()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **set_column_width()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **color_mapping()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **pytest_collection_modifyitems()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **pytester()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **restore_tracing()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **tw_mock()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **hookimpl** (1 connections)
- **Pytester** (1 connections)
- **Writes a conftest file that collects and executes a dummy yaml test. Taken from…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Returns a utility class which can replace keys in strings in the form "{NAME}"…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Restore tracing function (when run with Coverage.py).…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Mocks _pytest.timing with a known object that can be used to control timing in…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Make the test insensitive if it is running in CI or not. Use…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Force terminal width to 80: some tests check the formatting of --help, which is…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Reset all color-related variables to prevent them from affecting internal…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Prefer faster tests. Use a hook wrapper to do this in the beginning, so e.g.…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`
- **Returns a mock terminal writer** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`

## Relationships

- [Autouse Fixture Ordering](Autouse_Fixture_Ordering.md) (9 shared connections)
- [Cache Configuration](Cache_Configuration.md) (2 shared connections)
- [Mock Timing](Mock_Timing.md) (1 shared connections)
- [Fixture Capture](Fixture_Capture.md) (1 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/testing/conftest.py`

## Audit Trail

- EXTRACTED: 38 (97%)
- INFERRED: 1 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*