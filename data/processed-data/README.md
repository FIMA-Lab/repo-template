# Processed data / feature pipeline

<!-- Template modeled on the Elvis / 2026-Elvis-news-RV standard. Small derived files that
     the paper depends on are committed here; document the scripts that build them and the
     run order. Replace [ ... ] and delete these comments. -->

## Files

| File | Purpose | Input | Output |
|------|---------|-------|--------|
| `[build_step_1].py` | [what it computes] | `[raw input]` | `[intermediate output]` |
| `[build_step_2].ipynb` | [combine / feature-engineer] | `[inputs]` | `[feature file]` |

## Run order

1. `python [build_step_1].py`
2. Run `[build_step_2].ipynb`

## Feature files

| Type | File / Link |
|------|-------------|
| [Numerical features] | `[feature_file].csv` |
| [Other features] | [committed file, or external link if too large] |

## `utils.py` (optional)

| Index | Function | Description |
|-------|----------|-------------|
| 1 | `[function_name]` | [what it does] |
