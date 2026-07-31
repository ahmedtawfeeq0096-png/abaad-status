# Abaad — Status

Uptime monitoring for [Abaad](https://ar.agentlab-iq.com) (AR product menus).

- `uptime.yml` probes `/api/health` every 5 minutes (3 tries per run).
- An outage opens an issue in this repo; recovery closes it automatically.
- `keepalive.yml` commits a weekly heartbeat so GitHub never pauses the schedule.

No secrets, no customer data — just a URL and a status code.
