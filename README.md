# KMDB app

This bare-bones app runs [KMDB](https://github.com/HouseTrip/km-db) using Foreman.

Besides the KMDB environment variables, extra settings include:

- `RACK_ENV`
- `DATADOG_API_KEY`
- `APP_NAME`

to enable reporting of import staleness (using `bin/report-staleness`) to
[Datadog](http://www.datadoghq.com).
