# Assertion Truncation Tests

> 22 nodes · cohesion 0.13

## Key Concepts

- **TestMaterializeWithTruncation** (11 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **._config_with_limits()** (7 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **test_compare_recursive_dataclasses.py** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/dataclasses/test_compare_recursive_dataclasses.py`
- **test_recursive_dataclasses()** (5 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/dataclasses/test_compare_recursive_dataclasses.py`
- **C** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/dataclasses/test_compare_recursive_dataclasses.py`
- **._explain_capped()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **.test_does_not_over_consume_the_stream()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **.test_formatting_work_is_bounded_for_a_10_line_display()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **.test_idempotent_on_already_truncated_list()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **.test_sized_input_returns_same_shape_as_iterator_input()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **.test_truncation_disabled_returns_full_input()** (3 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **C2** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/dataclasses/test_compare_recursive_dataclasses.py`
- **C3** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/dataclasses/test_compare_recursive_dataclasses.py`
- **S** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/dataclasses/test_compare_recursive_dataclasses.py`
- **.test_pull_count_is_independent_of_input_size()** (2 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **Tests for ``truncate.materialize_with_truncation``.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **A list input truncates the same way as an iterator over it.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **Verbose >= 2 disables truncation; the iterator is fully drained.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **Re-truncating an already-truncated explanation changes nothing. The dispatcher…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **Laziness guard: the input iterator is never drained past the truncation…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **The number of lines pulled to truncate does not grow with the input.** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`
- **A huge comparison whose display is truncated to ~10 lines must not format the…** (1 connections) — `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`

## Relationships

- [Assertion Rewrite Tests](Assertion_Rewrite_Tests.md) (2 shared connections)
- [Text Diff Comparison](Text_Diff_Comparison.md) (2 shared connections)

## Source Files

- `raw/code/hyd-evaluation/pytest-harsha/testing/example_scripts/dataclasses/test_compare_recursive_dataclasses.py`
- `raw/code/hyd-evaluation/pytest-harsha/testing/test_assertion.py`

## Audit Trail

- EXTRACTED: 32 (94%)
- INFERRED: 2 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*