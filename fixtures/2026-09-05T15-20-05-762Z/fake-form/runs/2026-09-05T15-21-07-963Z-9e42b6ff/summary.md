# fake-form / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 4b254e17ede26510e6fd131807d62f2f3fe46e9bfbae908331c85e98e710b6e9

Resume is a local recheck, not a scheduler. 4 findings: contract 0; page 4; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1) > input:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1) > input:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
