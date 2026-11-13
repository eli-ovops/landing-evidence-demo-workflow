# json-dependency / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 6a0bf6018c2b4f9afc5f96a9cfc7006abfee552a0ffc5a2cdf2086c163e434f9

Resume is a local recheck, not a scheduler. 2 findings: contract 0; page 2; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /data.json: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /data.json: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
