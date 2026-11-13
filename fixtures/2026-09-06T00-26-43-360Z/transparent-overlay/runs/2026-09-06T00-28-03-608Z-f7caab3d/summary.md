# transparent-overlay / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 0d9cd4dbf92edc3a136a15c1ac87cd1397b333acc22572471e7b587553eedbf4

Resume is a local recheck, not a scheduler. 2 findings: contract 0; page 2; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
