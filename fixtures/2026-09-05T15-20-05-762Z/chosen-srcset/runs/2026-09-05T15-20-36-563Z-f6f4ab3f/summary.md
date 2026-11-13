# chosen-srcset / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: b98144c2005d303688e7a9c0eb15c159133481672312a16989459ddefd901fa6

Resume is a local recheck, not a scheduler. 4 findings: contract 2; page 2; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [desktop] #real: http://demo.local/broken.svg → SAME_VERSION_FIX
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [mobile] #real: http://demo.local/broken.svg → SAME_VERSION_FIX
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
