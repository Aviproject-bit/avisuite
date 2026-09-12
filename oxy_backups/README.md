# DATA BACKUP SHIELD - AviSuite
Every save and every deletion in the dashboards is a GIT COMMIT.
NOTHING is ever truly lost - full history of oxy_data/, shift_data/, caqc_data/
is preserved forever in this repository's commit log.

RECOVERY (any moment in time):
1. GitHub > this repo > Commits > pick the commit BEFORE the incident
2. Open oxy_data/data.json at that commit > download raw
3. Or simply message the AviSuite assistant: "restore oxy data from <date>"

SNAPSHOTS: dated copies live in oxy_backups/ (created at maintenance sessions
and on demand - say "backup now" to the assistant).
