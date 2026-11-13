# mobile-only / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 21aee9fe6a9f79284c140e20b75395054aac53b767826dd2e9fe4ed4657d1212

Resume is a local recheck, not a scheduler.

- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- FAIL MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- FAIL HORIZONTAL_OVERFLOW [mobile] document: 700 > required viewport 390 → SAME_VERSION_FIX

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
