# Max Warnings

> 24 nodes · cohesion 0.08

## Key Concepts

- **TestMaxWarnings** (13 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_equal_to_count()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_exceeded()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_exceeded_message()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_ini_option()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_not_exceeded()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_not_set()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_with_filterwarnings_error()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_with_filterwarnings_ignore()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_with_filterwarnings_ini_ignore()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_with_test_failure()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **.test_max_warnings_zero()** (4 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **Without --max-warnings, warnings don't affect exit code.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **When warning count is below the threshold, exit code is OK.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **When warning count exceeds threshold, exit code is MAX_WARNINGS_ERROR.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **When warning count equals threshold exactly, exit code is OK.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **--max-warnings 0 means no warnings are allowed.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **Verify the output message when max warnings is exceeded.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **max_warnings can be set via INI configuration.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **When tests fail AND warnings exceed max, TESTS_FAILED takes priority.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **Filtered (ignored) warnings don't count toward max_warnings.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **Warnings turned into errors via filterwarnings don't count as warnings.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **Warnings ignored via ini filterwarnings don't count toward max_warnings.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`
- **Tests for the --max-warnings feature.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`

## Relationships

- [Warnings Display](Warnings_Display.md) (12 shared connections)
- [Warning Filters](Warning_Filters.md) (11 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/testing/test_warnings.py`

## Audit Trail

- EXTRACTED: 46 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*