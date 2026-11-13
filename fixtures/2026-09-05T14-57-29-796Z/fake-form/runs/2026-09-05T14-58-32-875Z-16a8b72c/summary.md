# fake-form / active

Mechanical: FAIL; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: 3906d76924dd22578b16b77e025a8a0a226e5f2049c8caeb1f3811d2415e0796

Resume is a local recheck, not a scheduler. 4 findings; first 20 below, full list in result.json.

- FAIL FORM_OR_DATA_ENTRY [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- FAIL FORM_OR_DATA_ENTRY [desktop] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1) > input:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- FAIL FORM_OR_DATA_ENTRY [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX
- FAIL FORM_OR_DATA_ENTRY [mobile] html > body:nth-of-type(1) > main:nth-of-type(1) > form:nth-of-type(1) > input:nth-of-type(1): Static boundary: replace data collection / fake submission with registered real external path → SAME_VERSION_FIX

Next: Owner fix listed items in same version and rerun; only evidenced brand/IA/storyboard failure requires redesign
