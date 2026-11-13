# occluded / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 9b6ad594415ebecd55f6867446862d7379ea7a7ba220c6dca642ae2e06706388

Resume is a local recheck, not a scheduler. 14 findings; first 20 below, full list in result.json.

- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- FAIL HERO_CTA_NOT_VISIBLE [desktop] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- FAIL HERO_CTA_NOT_VISIBLE [mobile] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
