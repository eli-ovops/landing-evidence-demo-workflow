# Framed Focus / local-v1

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: bbdec7b1833d27efc115b53b9c3dc9dabea79c30c5c9438190c91240a18725c5

Resume is a local recheck, not a scheduler. 12 findings: contract 0; page 12; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL DUPLICATE_OR_EMPTY_ID [static] facebook-15: ID 必须全局唯一 → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL DUPLICATE_OR_EMPTY_ID [static] facebook-6: ID 必须全局唯一 → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL DUPLICATE_OR_EMPTY_ID [static] facebook-8: ID 必须全局唯一 → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL DUPLICATE_OR_EMPTY_ID [static] facebook-11: ID 必须全局唯一 → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL DUPLICATE_OR_EMPTY_ID [static] facebook-13: ID 必须全局唯一 → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL DUPLICATE_OR_EMPTY_ID [static] logo: ID 必须全局唯一 → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL ASSET_PATH_ESCAPE [static] facebook-15: originalPath invalid → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL ASSET_PATH_ESCAPE [static] facebook-6: originalPath invalid → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL ASSET_PATH_ESCAPE [static] facebook-8: originalPath invalid → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL ASSET_PATH_ESCAPE [static] facebook-11: originalPath invalid → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL ASSET_PATH_ESCAPE [static] facebook-13: originalPath invalid → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL ASSET_PATH_ESCAPE [static] logo: originalPath invalid → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
