# json-dependency / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: e53850f5b690d96589b51513faeff28d78ad5af0b19c1e1653dd735b4621a07f

Resume is a local recheck, not a scheduler. 2 findings; first 20 below, full list in result.json.

- FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /data.json: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /data.json: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
