# occluded / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 8690b6cd1a370fa8d672fd2db59d67f9a4f1ebbab3b1df75c53f044d61d27161

Resume is a local recheck, not a scheduler. 14 findings: contract 12; page 2; external/independent 0. Full detail is in result.json.

- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_NOT_VISIBLE [desktop] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_NOT_VISIBLE [mobile] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
