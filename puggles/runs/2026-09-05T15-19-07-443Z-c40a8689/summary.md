# Puggles Bath & Groom / demo_20260902/index.html

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 9c0c71d60fe03adc52a16f561e8854db2516a19d1288c7364495ecfc98700b61

Resume is a local recheck, not a scheduler. 17 findings: contract 9; page 2; external/independent 6. Full detail is in result.json.

- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BACKGROUND_PAINT_REVIEW [desktop] html > body:nth-of-type(1) > header:nth-of-type(1) > section:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → EXTERNAL_OR_INDEPENDENT_REVIEW
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I2: Expected {"selector":".feature-bath img","assetId":"A2"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I3: Expected {"selector":".care-visual img","assetId":"A3"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I9: Expected {"selector":"#hero-title","text":"Professional dog grooming in Reading."} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I10: Expected {"selector":".review-chip","text":"381+ Reviews"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [desktop] I14: Expected {"selector":".footer-links a[href*='facebook.com/pugglesdoggrooming']","text":"Facebook"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [desktop] .photo-hero .primary-button: Core CTA not within first screen → SAME_VERSION_FIX
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN EMBED_UNVERIFIED [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > section:nth-of-type(9) > div:nth-of-type(1) > iframe:nth-of-type(1): Remote iframe blocked; inspect registered src and independent rendering → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BACKGROUND_PAINT_REVIEW [mobile] html > body:nth-of-type(1) > header:nth-of-type(1) > section:nth-of-type(1): Background/pseudo decoded; paint occlusion, layering and crop require independent visual review → EXTERNAL_OR_INDEPENDENT_REVIEW
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I2: Expected {"selector":".feature-bath img","assetId":"A2"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I3: Expected {"selector":".care-visual img","assetId":"A3"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I10: Expected {"selector":".review-chip","text":"381+ Reviews"} → CONTRACT_RECONCILIATION
- CONTRACT_RECONCILIATION_BLOCKED / UNKNOWN MAPPED_CONTENT_NOT_VISIBLE_OR_MISMATCH [mobile] I14: Expected {"selector":".footer-links a[href*='facebook.com/pugglesdoggrooming']","text":"Facebook"} → CONTRACT_RECONCILIATION
- PAGE_RENDER_DEFECT / FAIL HERO_CTA_BELOW_FOLD_OR_OUTSIDE [mobile] .photo-hero .primary-button: Core CTA not within first screen → SAME_VERSION_FIX
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN EMBED_UNVERIFIED [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > section:nth-of-type(9) > div:nth-of-type(1) > iframe:nth-of-type(1): Remote iframe blocked; inspect registered src and independent rendering → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / LIMITATION REMOTE_RESOURCE_LIMITATION [static] desktop: document GET https://www.google.com/maps?q=3%20Mays%20Hill%20Cottages%2C%20Beech%20Hill%2C%20Reading%2C%20Berkshire%2C%20RG7%201JA&output=embed; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / LIMITATION REMOTE_RESOURCE_LIMITATION [static] mobile: document GET https://www.google.com/maps?q=3%20Mays%20Hill%20Cottages%2C%20Beech%20Hill%2C%20Reading%2C%20Berkshire%2C%20RG7%201JA&output=embed; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
