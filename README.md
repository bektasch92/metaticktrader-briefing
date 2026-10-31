# MetaTickTrader — Daily Briefing data

Written automatically every morning at 07:00 (Istanbul time) by a Claude scheduled task.
Read by `briefing.php` on metaticktrader.com (Daily Briefing tab).

- `briefing.json` — today's briefing (always the latest)
- `briefings/YYYY-MM-DD.json` — archive, one file per day (open with `briefing.php?date=YYYY-MM-DD`)

To fix or remove a bad briefing, edit or delete the file here on GitHub; the site picks it up within 10 minutes.
