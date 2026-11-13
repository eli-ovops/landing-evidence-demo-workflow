# mobile-only / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: e4cee4d5ee065b83010e39f4cfa528227e20dcffc59cc2998273311d6f846de1

Resume is a local recheck, not a scheduler. 4 findings: contract 3; page 1; external/independent 0. Full detail is in result.json.

- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL HORIZONTAL_OVERFLOW [mobile] document: 700 > required viewport 390 → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
