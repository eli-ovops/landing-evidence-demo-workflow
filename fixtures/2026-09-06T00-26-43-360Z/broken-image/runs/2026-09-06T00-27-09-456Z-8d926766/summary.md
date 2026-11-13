# broken-image / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: d7bbcf27cd71878c06badcf67493cbcfc343eda94a11fbc874e51a9f4775b32f

Resume is a local recheck, not a scheduler. 8 findings: contract 0; page 8; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [desktop] #real: http://demo.local/missing.svg → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [mobile] #real: http://demo.local/missing.svg → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
