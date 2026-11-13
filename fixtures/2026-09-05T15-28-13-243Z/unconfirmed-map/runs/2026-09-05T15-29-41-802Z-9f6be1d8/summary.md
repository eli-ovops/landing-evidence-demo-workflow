# unconfirmed-map / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: ebfc834302188e9f17f15822e509134fdb484e17c6d0cdcaa028502750b3b742

Resume is a local recheck, not a scheduler. 7 findings: contract 3; page 4; external/independent 0. Full detail is in result.json.

- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_CONFIRMATION_PENDING [static] I-logo: global reconciled coverage cannot leave item mapping unconfirmed → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [mobile] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HORIZONTAL_OVERFLOW [mobile] document: 624 > required viewport 390 → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
