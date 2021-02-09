# e7-rta

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/etothex2/e7-rta/HEAD)

Code to explore and enrich Epic 7 RTA data puled by `u/Gskip`. Example Notebook with all ETL code can be run interactively using the above binder link.

### Data Enrichment
* Type casting
* Reorder columns
* Add match_id primary key
* Add `WIN` variable as bool
* Add `str` column with the full team of each player
* Calculate # of matches for each player
* Calculate winrate of each player
* Calculate difference in winrate between P1 and P2
* Convert epoch time to timestamp
* `battle_logs_by_player` table that contains metrics at a player level

### Adhoc Pulls (WIP)
* Preban by League
