# missing-cta / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: e6746cff4c388fc04a7e1809932936f1855dcd7285d7886f639b3d1f43443f89

Resume is a local recheck, not a scheduler. 6 findings; first 20 below, full list in result.json.

- FAIL MAPPING_MISSING [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [desktop] #cta: Core CTA not within first screen → SAME_VERSION_FIX
- FAIL HERO_CTA_NOT_VISIBLE [desktop] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX
- FAIL MAPPING_MISSING [mobile] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [mobile] #cta: Core CTA not within first screen → SAME_VERSION_FIX
- FAIL HERO_CTA_NOT_VISIBLE [mobile] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
