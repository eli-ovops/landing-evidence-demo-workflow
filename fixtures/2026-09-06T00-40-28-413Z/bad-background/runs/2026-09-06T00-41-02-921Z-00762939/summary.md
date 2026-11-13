# bad-background / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: b4ddac2f34fb3834f448832d03f69a8679766f1aa1807536e87d70bf51aedd87

Resume is a local recheck, not a scheduler. 4 findings: contract 0; page 2; external/independent 2. Full detail is in result.json.

- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BACKGROUND_PAINT_REVIEW [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → EXTERNAL_OR_INDEPENDENT_REVIEW
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): http://demo.local/broken.svg → SAME_VERSION_FIX
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BACKGROUND_PAINT_REVIEW [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → EXTERNAL_OR_INDEPENDENT_REVIEW
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): http://demo.local/broken.svg → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
