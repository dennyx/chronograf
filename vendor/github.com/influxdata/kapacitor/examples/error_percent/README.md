Example Calculating Error Percent on Joined series
==================================================

See https://influxdb.com/docs/kapacitor/v0.1/use_cases/join_backfill.html
for a complete guide.

TL;DR
-----

Run:

```
# load random error and view data into dates 2015-01-01 to 2015-01-11
load.sh
# Backfill the error percentage for those dates.
backfill.sh
```

