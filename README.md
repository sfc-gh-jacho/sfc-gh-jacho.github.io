# Snowflake Hands-on Guides

**Owner:** Janet Cho · **Last reviewed:** November 2026 · **License:** [Apache 2.0](LICENSE)

Landing page for a set of self-contained Snowflake walkthroughs. Each guide ships with copy-and-run SQL, synthetic data and real results.

**Live site:** https://sfc-gh-jacho.github.io/

## Guides

| Guide | Topic | Repository |
|---|---|---|
| [Protecting PII in Snowflake](https://sfc-gh-jacho.github.io/sfguide-pii-data-protection/) | Classification, tag-based masking, masking and row access policies | [sfguide-pii-data-protection](https://github.com/sfc-gh-jacho/sfguide-pii-data-protection) |
| [Cost Chargeback with Tags](https://sfc-gh-jacho.github.io/sfguide-cost-chargeback-tagging/) | Object tags, resource monitors, budgets, chargeback queries | [sfguide-cost-chargeback-tagging](https://github.com/sfc-gh-jacho/sfguide-cost-chargeback-tagging) |
| [Regulatory Reporting with Time Travel](https://sfc-gh-jacho.github.io/sfguide-regulatory-audit-time-travel/) | Time Travel, clones, streams, access history, UNDROP | [sfguide-regulatory-audit-time-travel](https://github.com/sfc-gh-jacho/sfguide-regulatory-audit-time-travel) |
| [Trade Surveillance in Snowflake](https://sfc-gh-jacho.github.io/sfguide-trade-surveillance/) | MATCH_RECOGNIZE, window functions, Dynamic Tables, masking | [sfguide-trade-surveillance](https://github.com/sfc-gh-jacho/sfguide-trade-surveillance) |

## Adding a guide

Copy one `<article class="guide-card">` block in `index.html`, then update the title, links, feature chips and metadata. Add a matching row to the table above and a link in the footer.

## Repository layout

```
index.html    Landing page (static, no third-party requests)
styles.css    Shared styling with the guides (Snowflake palette)
script.js     Mobile navigation and scroll effects
LICENSE       Apache License 2.0
```

## Disclaimer

All data in the guides is synthetic. Illustrative calculations are not regulatory, compliance or financial advice. The repository contains no credentials, account identifiers or connection details.
