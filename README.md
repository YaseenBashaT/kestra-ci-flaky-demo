# kestra-ci-flaky-demo

Test repository for the Kestra blueprint `github-actions-flaky-or-broken`.

`mode.txt` decides how the CI run on `main` behaves:

- `ok`: every job passes.
- `flaky`: the `integration` job fails on the first attempt and passes when it is re-run, like a flaky test.
- `broken`: the `unit` job fails on every attempt, like a real regression.
# still broken
