# broken-image / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 222c3d70c0c7c8e026c88ee2a969fd0a6474bc664c44c81c62c18988eaabebc9

Resume is a local recheck, not a scheduler. 8 findings; first 20 below, full list in result.json.

- FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [desktop] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- FAIL BROKEN_IMAGE [desktop] #real: http://demo.local/missing.svg → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- FAIL LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED [mobile] /missing.svg: Local dependency missing or outside supported static types/active root; do not broaden reads → SAME_VERSION_FIX
- FAIL BROKEN_IMAGE [mobile] #real: http://demo.local/missing.svg → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
