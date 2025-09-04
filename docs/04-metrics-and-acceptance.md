# Metrics & Acceptance

Metrics: capture_time_ms · entries_per_week · search_to_open_rate · median_search_time_ms · reuse_rate_30d · secret_scan_flags_count

Acceptance:
- AT-01 Quick save: Tier 0 save shows toast ≤1s
- AT-02 Exact phrase: quoted error appears top 3
- AT-03 Facets: combining lang + type filters correctly
- AT-04 Secret warning: conn string triggers banner with “Redact & Save / Save anyway”
- AT-05 Duplicate hint: identical error within 180d suggests up to 3 entries
- AT-06 Quick-copy: detail view copies Fix Summary
