# network / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: e0fff1eab05388a1978ddeca61e030bd42b983028142b866778e69130ffcabef

Resume is a local recheck, not a scheduler. 16 findings: contract 7; page 2; external/independent 7. Full detail is in result.json.

- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [desktop] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [desktop] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [desktop] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPING_MISSING [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → CONTRACT_RECONCILIATION
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
