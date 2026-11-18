# reports

The daily sealhouse delivery report, published at https://sealhouse.github.io/reports.

`data/daily/YYYY-MM-DD.json` is one day's report and `data/rollup.json` the series the site charts.
ci's `sealhouse-report` workflow commits both every day, and `sealhouse-pages` builds and deploys the site from them.
