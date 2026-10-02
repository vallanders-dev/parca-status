# Parça status

Uptime check for [Parça](https://parcaplay.com): every 10 minutes GitHub Actions
checks the companion server (`api.parcaplay.com/v1/health`) and the website.
An outage opens an `[uptime]` issue here (and GitHub emails the owner); it
closes by itself when everything is back.

Nothing private lives here - only the workflow in `.github/workflows/uptime.yml`.
