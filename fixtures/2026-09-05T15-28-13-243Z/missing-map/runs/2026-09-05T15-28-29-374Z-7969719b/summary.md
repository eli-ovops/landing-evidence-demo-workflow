# missing-map / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 0d335c777a84a5c1d842d6be21b505d156e2ca7179b1bc6c42fc2976536ad94e

Resume is a local recheck, not a scheduler. 2 findings: contract 0; page 2; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
