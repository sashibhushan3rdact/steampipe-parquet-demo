# steampipe-parquet-demo

Sample GitHub repository used as the data source for a `GitHub -> Steampipe -> Parquet`
extraction pipeline demo.

It intentionally contains outdated, vulnerable npm dependencies (see `package.json`) so
that GitHub Dependabot raises real alerts, plus sample issues and pull requests, so the
`github_repository`, `github_issue`, `github_pull_request`, and `github_dependabot_alert`
Steampipe tables all have real data to query.

## Status

Actively maintained demo repository.
