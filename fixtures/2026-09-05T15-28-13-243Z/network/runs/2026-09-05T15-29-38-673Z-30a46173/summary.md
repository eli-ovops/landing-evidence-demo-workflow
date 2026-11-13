# network / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 0d945f0194a711324558ac6e76d06cf8703b4cac028db8b2d1656b51ddaa2658

Resume is a local recheck, not a scheduler. 16 findings: contract 1; page 8; external/independent 7. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPING_MISSING [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN HERO_MISSING [desktop] #hero: missing → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [desktop] #cta: Core CTA not within first screen → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_NOT_VISIBLE [desktop] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BROWSER_CHECK_BLOCKED [static] mobile: page.evaluate: Execution context was destroyed, most likely because of a navigation. → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] desktop: fetch POST https://example.invalid/write; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] desktop: ping POST https://example.invalid/beacon; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] desktop: document GET https://example.invalid/navigate; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] mobile: fetch POST https://example.invalid/write; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] mobile: ping POST https://example.invalid/beacon; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] mobile: document GET https://example.invalid/navigate; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
