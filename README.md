# qe-plans-and-reports

Published per PR against `cialfo/app-cialfo-core-web`, served via GitHub Pages
at `cialfo.github.io/qe-plans-and-reports/`. Two kinds of content live here,
both auto-published — no manual commits:

- `pr-<PR_NUMBER>/` — a QE test plan, published by the Paperclip QE automation agent.
- `regression-pr-<PR_NUMBER>/<run_id>/` — an Allure regression-suite report,
  published by `core-pw-e2e-tests`' CI when someone comments
  `/execute-regression-suite` on a core-web PR. Pruned after 30 days.
- `allure-history/latest/` — rolling trend history consumed by the next
  regression run; not meant to be browsed directly.
