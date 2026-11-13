# confirmed-map / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 4cf126e000a6fc337d4dace455e282f297e94611e11dfa0821f522f8d0f29f51

Resume is a local recheck, not a scheduler. 6 findings: contract 0; page 6; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [mobile] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HORIZONTAL_OVERFLOW [mobile] document: 624 > required viewport 390 → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
