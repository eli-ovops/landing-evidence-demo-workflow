# json-dependency / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 1a3eaa62819d899fd68362259d0426ff47a1e05a09e37b5317a345bb8299059a

Resume is a local recheck, not a scheduler. 2 findings: contract 0; page 2; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /data.json: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /data.json: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
