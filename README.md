# Rasa Conditional Response Variation Examples & Tests

## Rasa Test Stories

Run the following commands and review the `results/failed_test_stories.yml` for errors

```sh
rm results/failed_test_stories.yml
rasa test -s tests/test_stories.yml  
```

## Rasa Pro e2e Test

Run the following commands and review the `tests/e2e_results.yml` for errors

```sh
rm tests/e2e_results.yml
rasa test e2e -o
```
