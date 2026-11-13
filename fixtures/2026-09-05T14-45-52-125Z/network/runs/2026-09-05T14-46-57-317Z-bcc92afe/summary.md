# network / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 430affbd4065282977fe80d64c8ae496707cbdb28c0f3c9a1ceb56dd75c84488

Resume is a local recheck, not a scheduler.

- FAIL MAPPING_MISSING [desktop] I-logo: Expected {"selector":"#logo","assetId":"A-logo"} → SAME_VERSION_FIX
- FAIL MAPPING_MISSING [desktop] I-real: Expected {"selector":"#real","assetId":"A-real"} → SAME_VERSION_FIX
- FAIL MAPPING_MISSING [desktop] I-fact: Expected {"selector":"#fact","text":"Care for your dog"} → SAME_VERSION_FIX
- FAIL MAPPING_MISSING [desktop] I-map: Expected {"selector":"#map","text":"Get directions","href":"https://example.invalid/map"} → SAME_VERSION_FIX
- FAIL MAPPING_MISSING [desktop] I-social: Expected {"selector":"#social","text":"See our work","href":"https://example.invalid/social"} → SAME_VERSION_FIX
- FAIL MAPPING_MISSING [desktop] I-cta: Expected {"selector":"#cta","text":"Call the salon","href":"tel:+441234567890"} → SAME_VERSION_FIX
- FAIL HERO_MISSING [desktop] #hero: missing → SAME_VERSION_FIX
- FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [desktop] #cta: Core CTA not within first screen → SAME_VERSION_FIX
- FAIL HERO_CTA_NOT_VISIBLE [desktop] #cta: CTA hidden/clipped/occluded → SAME_VERSION_FIX
- UNKNOWN BROWSER_CHECK_BLOCKED [static] mobile: page.evaluate: Execution context was destroyed, most likely because of a navigation. → OWNER_EVIDENCE
- UNKNOWN NETWORK_BLOCKED [static] desktop: fetch POST https://example.invalid/write; destination behavior not verified → OWNER_EVIDENCE
- UNKNOWN NETWORK_BLOCKED [static] desktop: ping POST https://example.invalid/beacon; destination behavior not verified → OWNER_EVIDENCE
- UNKNOWN NETWORK_BLOCKED [static] desktop: document GET https://example.invalid/navigate; destination behavior not verified → OWNER_EVIDENCE
- UNKNOWN NETWORK_BLOCKED [static] mobile: fetch POST https://example.invalid/write; destination behavior not verified → OWNER_EVIDENCE
- UNKNOWN NETWORK_BLOCKED [static] mobile: ping POST https://example.invalid/beacon; destination behavior not verified → OWNER_EVIDENCE
- UNKNOWN NETWORK_BLOCKED [static] mobile: document GET https://example.invalid/navigate; destination behavior not verified → OWNER_EVIDENCE

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
