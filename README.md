# Daily Product Stats

Automated daily product metrics pulled from Datadog and BigQuery, posted to Slack by a [Claude Code scheduled trigger](https://docs.anthropic.com/en/docs/claude-code).

Runs every weekday at 12:30 UTC. Stats are posted to `#product-engineering-sync` and `#leadership-team`, and committed here as a daily log.

## Metrics tracked

**Latency (p95)**
- App (Microportal)
- FIS Delegated Auth
- Direct Preauth

**Volume (7-day rolling)**
- Card Swipes
- Card Activations (App/Portal)

**Item Stats**
- Active SKUs across merchant listings (from BigQuery `merchant.item` + `merchant.merchant_item`)
- Item Approval Rate (7-day rolling)

**Digital Engagement (7-day rolling)**
- IVR Containment
- SMS Opt-in at Registration

**Adjudication**
- Model Match Rate

## Structure

```
2026/
  05/
    2026-05-01.md
    2026-05-02.md
    ...
```

Each daily file contains the same formatted stats posted to Slack.
