# bad-background / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: d281bc16dfd0663bf393b79cbb17a342040fbd64efd07902de0fa8d10fce561c

Resume is a local recheck, not a scheduler.

- UNKNOWN BACKGROUND_PAINT_REVIEW [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → OWNER_EVIDENCE
- FAIL BROKEN_IMAGE [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): http://demo.local/broken.svg → SAME_VERSION_FIX
- UNKNOWN BACKGROUND_PAINT_REVIEW [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → OWNER_EVIDENCE
- FAIL BROKEN_IMAGE [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > div:nth-of-type(1): http://demo.local/broken.svg → SAME_VERSION_FIX

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
