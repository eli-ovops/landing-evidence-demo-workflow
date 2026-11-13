# fake-form / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 843171813b64e3dd1d0785930bbd4d2c6c69cb8f752b5d18ebcc8df225c6cff5

Resume is a local recheck, not a scheduler. 4 findings: contract 0; page 4; external/independent 0. Full detail is in result.json.

- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1) > input:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- PAGE_RENDER_DEFECT / FAIL FORM_OR_DATA_ENTRY [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1) > input:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
