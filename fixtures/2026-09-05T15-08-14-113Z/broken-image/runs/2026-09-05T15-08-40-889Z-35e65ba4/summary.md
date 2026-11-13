# broken-image / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 2e36e680d8869c7110a044f34f95fda5cc4953f9e47db3fb46f3fa601bf67e66

Resume is a local recheck, not a scheduler. 8 findings: contract 2; page 6; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [desktop] #real: http://demo.local/missing.svg → SAME_VERSION_FIX
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [mobile] #real: http://demo.local/missing.svg → SAME_VERSION_FIX
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
