# occluded / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: a1838ffc566754c5ac116cae9faab0cf26754d489377023f009a632486f82b94

Resume is a local recheck, not a scheduler. 14 findings: contract 0; page 14; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_NOT_VISIBLE [desktop] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_NOT_VISIBLE [mobile] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
