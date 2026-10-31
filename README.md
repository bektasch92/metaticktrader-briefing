# MetaTickTrader — Daily Briefing data

Written automatically every morning (~07:00 Istanbul time) by a Claude scheduled task.
Read by `briefing.php` on metaticktrader.com (Daily Briefing tab).

- `briefing.json` — the latest briefing
- `briefings/YYYY-MM-DD.json` — archive, one file per day (`briefing.php?date=YYYY-MM-DD`)
- `briefings/index.json` — list of all briefings, newest first (`briefing.php?archive=1`)

Sundays add `weekly_summary` (week in review); Mondays add `week_ahead` (what to expect this week).

To fix or remove a bad briefing, edit or delete the file here on GitHub (and its line in index.json); the site picks it up within 10 minutes.
