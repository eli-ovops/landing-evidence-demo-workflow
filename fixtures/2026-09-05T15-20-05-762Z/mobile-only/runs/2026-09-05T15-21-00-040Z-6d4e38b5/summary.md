# mobile-only / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 3dc7aaf44665f3710c71a0181d50d55cb7adca1a3374274d00774dfd591d9eb9

Resume is a local recheck, not a scheduler. 4 findings: contract 3; page 1; external/independent 0. Full detail is in result.json.

- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL HORIZONTAL_OVERFLOW [mobile] document: 700 > required viewport 390 → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
