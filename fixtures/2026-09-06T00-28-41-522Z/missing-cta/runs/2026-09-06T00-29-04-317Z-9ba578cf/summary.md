# missing-cta / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 4f259c521b63dfc5710f772846d9bbcb66478414b0f9a7fa2f30c1a5322b1e2b

Resume is a local recheck, not a scheduler. 6 findings: contract 0; page 6; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [desktop] #cta: Core CTA not within first screen → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_NOT_VISIBLE [desktop] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [mobile] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [mobile] #cta: Core CTA not within first screen → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_NOT_VISIBLE [mobile] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
