# bad-background / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 01cde3d8819af0b90640e1ea1e8a3acb20c093059803715aaf4178a8ce69c951

Resume is a local recheck, not a scheduler. 4 findings: contract 0; page 2; external/independent 2. Full detail is in result.json.

- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BACKGROUND_PAINT_REVIEW [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → EXTERNAL_OR_INDEPENDENT_REVIEW
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): http://demo.local/broken.svg → SAME_VERSION_FIX
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BACKGROUND_PAINT_REVIEW [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → EXTERNAL_OR_INDEPENDENT_REVIEW
- PAGE_RENDER_DEFECT / FAIL BROKEN_IMAGE [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): http://demo.local/broken.svg → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
