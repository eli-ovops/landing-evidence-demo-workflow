# missing-social / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: fca027108cf2187d1c40b0ecea080eada8837ec88a039c72830320fcb6a1697f

Resume is a local recheck, not a scheduler. 2 findings: contract 0; page 2; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
