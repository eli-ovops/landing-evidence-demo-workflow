# chosen-srcset / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: a94d99dff5b4d434079ad64a69058a421b93af0d21b747bd4d2cb96a14b87efe

Resume is a local recheck, not a scheduler. 4 findings: contract 0; page 4; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [desktop] #real: http://demo.local/broken.svg → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [mobile] #real: http://demo.local/broken.svg → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
