# Demo workflow engineering — Owner implementation evidence

Status: 待独立审查。This report does not claim customer-demo acceptance, deployment, outreach, source transfer, commercial outcome, or unattended operation.

## Runnable entry points

```sh
node tools/demo-workflow/cli.mjs doctor
node --test tools/demo-workflow/test.mjs
node tools/demo-workflow/cli.mjs status --job /Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/washy-washy
node tools/demo-workflow/cli.mjs status --job /Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/puggles
node tools/demo-workflow/cli.mjs status --job /Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/lilux
```

The CLI uses native Node JSON and the already-present Playwright/Chrome runtime. No package was installed. `init` imports the active page plus explicitly allowlisted existing source files, builds an independent source baseline and keeps source rows `UNMAPPED` until Owner reconciliation; it cannot use only present DOM content as false coverage. `run` binds contract, static-page manifest, source files and checker hashes; `resume` is a local full recheck and is not a scheduler.

## Reviewer-specific repair matrix

| Finding | Implemented evidence |
| --- | --- |
| Hash then reread mutable bytes | `core.mjs#fingerprint` snapshots bytes into a Map; `browser.mjs#inspect` serves the snapshot only; `test.mjs` immutable-snapshot test changes disk after fingerprint and confirms original hash snapshot renders. |
| Unsupported/local resource gaps | Manifest permits only declared static types inside the concrete active root; local missing/unsupported dependencies are `LOCAL_RESOURCE_MISSING_OR_UNSUPPORTED`; `../`, symlink, project root, other customer root and output-in-customer-root are rejected. |
| Visible coverage | `visible()` scrolls normal below-fold targets, rejects opacity/size/hidden/occluded targets; pseudo/background decoded media yields `BACKGROUND_PAINT_REVIEW=UNKNOWN`, never automatic visual PASS. |
| Hidden text / local href / Hero | Actual `innerText` only; local href targets are checked; Hero CTA checks first-screen, horizontal bounds and visibility. |
| External behavior | Offline snapshot blocks every external request, fetch/xhr/ping, form submission and WebSocket; attempted destination navigation is emitted as `NETWORK_BLOCKED=UNKNOWN`. No calls, messages, forms, beacons or tracking execute. |
| Independent baseline | Duplicate IDs, all-EXCLUDE, empty exclusion, missing/unmapped source baseline, stale source hash and missing asset mappings fail. A source baseline is extracted independently of DOM. |
| Resume/repeat/stale evidence | Atomic job/result state, PID lock, interrupted lock receipt, owner match, input fingerprint and all evidence hashes are checked; tests cover partial status, repeat run, input changes and screenshot tamper. |
| Final acceptance spoofing | `CLIENT-SHOWABLE` remains `AWAITING INDEPENDENT REVIEW`; `review-check` requires distinct structured reviewer provenance, result/input/evidence hashes, viewport/business/asset findings. A generic reviewer string or `finalPass` fails structural binding. PMO still verifies identity independently. |

## Regression proof

Raw output: [test-output-20260905.txt](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/test-output-20260905.txt). The suite has eight tests and 18 explicit red-to-green defect cases: missing logo/real image/map/social/CTA; broken chosen `srcset` and background image; opacity/zero-size/occlusion/hidden-text; mobile-only overflow; runaway hero; form/internal text; local broken link; unsupported JSON dependency. It also covers snapshot immutability, source baseline retention, scope/symlink escape, state/repeat/resume/evidence tampering and blocked network behavior.

## Three historical current-version read-only replays

| Customer | Active page binding | Input hash | Result | Raw evidence |
| --- | --- | --- | --- | --- |
| Washy Washy | `demo_20260902/index.html` SHA `cdc9f5a…` equals existing local-preview index | `3b4c1fb906c8d28f83c4b7da31e3b0cfe89f8ee5e78b46fc1154e368eb9724a8` | Mechanical FAIL, final review awaiting | [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/washy-washy/runs/2026-09-05T14-57-00-088Z-8ea58184/result.json) |
| Puggles Bath & Groom | `demo_20260902/index.html` SHA `934fe17d…` equals existing local-preview index | `dc0b658ca0ddb7ab9434eb95400c3ddb5ff9f705f6a21673fb18e3bce883a0dc` | Mechanical FAIL, final review awaiting | [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/puggles/runs/2026-09-05T14-57-00-073Z-ef4f7d5e/result.json) |
| Lilux Developments | `v6/index.html` SHA `83a7328c…`; `v6/style.css` SHA `3a356cc7…` matches current local-preview manifest | `78f458b806aa9df05f9e06ded569d19944a5b83ed097224a73063b97e3f34771` | Mechanical FAIL, final review awaiting | [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/lilux/runs/2026-09-05T14-57-00-073Z-3deb8f66/result.json) |

All three failures are evidence findings, not changes to customers: independent source baselines remain unreconciled; generated DOM observations intentionally lack source-grade/fact reconciliation; offline validation leaves remote map/font/embed behavior UNKNOWN. The raw `browser.json`, `inputs.json`, full/top desktop/mobile PNGs and `visual-review-tasks.json` reside next to each result. Existing customer files were only read; hashes above prove no change during this replay.

## Rules change evidence

The `before/` directory contains pre-change copies and SHA-256 values for the four changed authority files. The final rule text consistently routes local implementation/content omissions to active-version fix and recheck, and reserves `FAIL — REDESIGN DIRECTION` for substantiated brand/IA/Hero/full-storyboard failure. It permits generic unbranded primitives without allowing customer asset or finished-page reuse. See `git diff --no-index evidence/demo-workflow-20260905/before/<file> <file>` (exit 1 denotes an expected diff in this non-Git workspace).

## Limits for independent review

The checker does not judge crop aesthetics, underlying business truth, visual quality, commercial increment, external destination behavior, or human Reviewer identity. Those limitations are intentional and emitted as tasks/UNKNOWN rather than PASS. Review current result/evidence hashes before relying on any conclusion; any contract/page/CSS/JS/asset/source/checker change invalidates it.

## Latest owner regression and replay evidence — 2026-09-05

Single-session command `node --test --test-concurrency=1 tools/demo-workflow/test.mjs` completed naturally with tool `exit_code: 0`: 11/11 PASS, including the confirmed-versus-unconfirmed mapping classification and source-linked baseline structure regressions. Raw TAP transcript: [test-output-20260905-final.tap](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/test-output-20260905-final.tap).

Checker hashes: `core.mjs 3835c5ed4b4e697c68cb27c3fac20072b35097082db5281ac78137e89801d21e`; `browser.mjs 3e7b010075cf75dac98ee6b69989fc076833fe8e9ecf98938d5ff3818fc8b59f`; `cli.mjs 7346b822729975e77c7d13f96c48b3e10b66777779c4e94885460aa5b504130d`; `test.mjs 476e9d33412ace0e1be96961f208743d77c80b101a922e3cffb777693784d2a0`.

Latest same-checker replays: Washy `ef9f5d40fedb079ef927693dc92a117289dc0fc1805281789f6e2a3bdbb91ca3` [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/washy-washy/runs/2026-09-05T15-30-02-517Z-b276f4a7/result.json); Puggles `44614ad3b108cbb87e2a44a939959d68d7285a650bf2260e7cd471823a79b7b5` [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/puggles/runs/2026-09-05T15-30-09-638Z-546d5224/result.json); Lilux `8cd2a8f8094b7b61dfb64036435b20887dc233fc0ba81b71bb560e54cd83d7b7` [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/lilux/runs/2026-09-05T15-30-16-147Z-6e4e5a6a/result.json). Puggles has zero contract reconciliation findings; its retained page defect is the real Hero CTA first-screen failure, with independent visual/remote-map review still pending.

## Latest superseding evidence — 2026-09-06

The prior 2026-09-05 replay table is historical only. A Hero false positive was fixed by resetting the browser to `scroll-behavior: instant` top-of-page coordinates before Hero evaluation and choosing a first-screen matching CTA. Sibling overlay handling now rejects opaque sibling covers while retaining semi-transparent overlays and emitting independent visual review for complex background/pseudo paint.

Single-session current suite: [test-output-20260906.tap](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/test-output-20260906.tap), session `6962`, tool `exit_code: 0`, 12/12 PASS. Current checker hashes: core `3835c5ed4b4e697c68cb27c3fac20072b35097082db5281ac78137e89801d21e`; browser `053d4fc0004e6cc67be6ca3f934fb83ebf8778251b4b47c720d9cbda758eb2be`; cli `7346b822729975e77c7d13f96c48b3e10b66777779c4e94885460aa5b504130d`; test `390cf3f669cae253bbd3991c4141c0e21b8ba78372c2373ea3f8c1963fde9cbc`.

Current replays: Washy [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/washy-washy/runs/2026-09-06T00-31-59-912Z-f09c90e5/result.json) input `a7190894c77bf278d4512b65ab25444dd1decb3070bfba6cf4fad627bc02b2cc`, mechanical FAIL; Puggles [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/puggles/runs/2026-09-06T00-32-05-011Z-9e9910dc/result.json) input `d07ded3b6d3c546b9c0a135fd4354cb2ff6827c509a6097d0d8b7470730eaddd`, contract 0 / page 0 / external-independent 6, mechanical UNKNOWN; Lilux [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/lilux/runs/2026-09-06T00-32-10-791Z-62c1a8f7/result.json) input `577f611b844b21663b54870e4293317ae7ed95a4738b0b3708459f61a7f05bb3`, mechanical FAIL. Puggles is ready for independent review of the explicitly hash-bound visual and external limitations; no Client-showable verdict is granted.

Disk note: this task's evidence directory is 255MB, generated by browser screenshots and fixture runs; no cleanup was authorized or performed.

### Test receipt correction

`test-output-20260906.tap` is a compact reviewer summary, not the authoritative raw receipt. The authoritative direct-tool stdout is [test-run-20260906-session-20203.tap](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/test-run-20260906-session-20203.tap), SHA-256 `e81d63e1e77c5af07c43b7f18a978ec5dd4040c4e714c36a70d5172690c6d6ac`; its machine receipt is [test-run-20260906-session-20203.receipt.json](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/test-run-20260906-session-20203.receipt.json), SHA-256 `d674ffdb360abfb7261db27029b90f9b39aecf85198ab537edd4d01d1e398320`. Command: `node --test --test-concurrency=1 tools/demo-workflow/test.mjs`; direct session `20203` ended naturally with actual `exit_code: 0`, 12 pass / 0 fail. Tool hashes are core `3835c5ed4b4e697c68cb27c3fac20072b35097082db5281ac78137e89801d21e`, browser `053d4fc0004e6cc67be6ca3f934fb83ebf8778251b4b47c720d9cbda758eb2be`, cli `7346b822729975e77c7d13f96c48b3e10b66777779c4e94885460aa5b504130d`, test `390cf3f669cae253bbd3991c4141c0e21b8ba78372c2373ea3f8c1963fde9cbc`.

## Reconciliation replay correction — 2026-09-06 13:43Z

The earlier statement that Washy/Lilux reconciliation was being completed was incorrect: both contracts remained source-only initialization drafts (`coverageReview` was still pending; every imported source/fact mapping retained `UNKNOWN`). No customer page was edited. `confirm-current-mappings` correctly refused `COVERAGE_NOT_RECONCILED`; it was not used to manufacture an Owner confirmation.

Two new same-version, local, offline runs were then recorded to preserve the actual state: Washy [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/washy-washy/runs/2026-09-06T13-43-37-497Z-a61b1957/result.json), SHA-256 `399526f8734203791042344cfa4c81889c06a0cfe01a61980afa088db3da79ca`, input `a7190894c77bf278d4512b65ab25444dd1decb3070bfba6cf4fad627bc02b2cc`, is Mechanical FAIL with contract 211 / page 0 / external 0. Lilux [result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/lilux/runs/2026-09-06T13-43-48-138Z-0f3c7f99/result.json), SHA-256 `38c62573af298cea1c20f916ed82dbef7756d07f85ead4dded272992ef9844ce`, input `577f611b844b21663b54870e4293317ae7ed95a4738b0b3708459f61a7f05bb3`, is Mechanical FAIL with contract 597 / page 0 / external 6. Both remain `AWAITING INDEPENDENT REVIEW`; their contract findings are `CONTRACT_RECONCILIATION_BLOCKED`, not page defects. The six Lilux external findings remain explicit offline/independent-review UNKNOWNs.

This is not a completed source reconciliation. The required next Owner work is to replace the DOM-derived draft records with individually supported source/asset/fact mappings (including the V3/V6 provenance conflict) before another run. Puggles was not run or modified. Customer index hashes remain Washy `cdc9f5a6684b463fc2fef9ad2a1020f1be3deb29d680618bad01e63b8369df73`, Puggles `934fe17d35c871660824e346165ca2c20d7d5cbe7fd4533b537faef06f586443`, Lilux `83a7328c8d013752a633f6f2bfdab9677f7892672894771132fe2adf4d58aa2d`.

## Washy source reconciliation — 2026-09-06 13:49Z

Washy is now individually reconciled from existing local originals, without changing its customer page. Contract SHA-256: `7a4f71b8efa5394755983575b18fdfd3deb019427e6e7b6fff5dfef731100843`. Examples: inventory `ASSET_INVENTORY.csv:2` (`official-logo`, matching hash) → source `S1` → asset `A1` → `.brand img`; intelligence `CUSTOMER_PUBLIC_INTELLIGENCE.md:9` (mobile doorstep trailer) → `S1` → `I7` → `.hero-copy`; intelligence `:10` (public phone) → `S1` → `I13` → `.booking-number`, `tel:+447466669399`. Third-party coverage/Trustpilot claims use separate `S2`, are marked `SOURCE CLAIM`; the score is `TIME-SENSITIVE VERIFY/REPHRASE`. The two old generated concept assets are explicitly excluded because neither is in the active page and the ledger requires replacement/exclusion before handover.

The new hash-bound [Washy result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/washy-washy/runs/2026-09-06T13-49-10-547Z-d715c891/result.json), SHA-256 `224ed8450f91b8630cdf09173f09331303723c72cefceb943cbaf469086d0884`, input `92f2af03bbb86622b9b9cd2dcca92c66bfa4c9ca3f86ec25f63507a0e5fd67df`, has contract `0`, external `0`, and exactly one PAGE_RENDER_DEFECT: mobile `.hero-facts a` is below the first screen (`HERO_CTA_BELOW_FOLD_OR_OUTSIDE`). This is a same-active-version repair item, not direction-level redesign. `CLIENT-SHOWABLE` remains `AWAITING INDEPENDENT REVIEW`; no customer page was altered.

## Lilux V3/V6 conflict record — 2026-09-06 13:52Z

Lilux contract SHA-256 is now `96ed60ef485ad2943687d276927c3eae6a8da5301cb92ac8a7b2943457ca07c6`. Two individual historical statements are marked `SUPERSEDED`, not silently discarded: intelligence `CUSTOMER_PUBLIC_INTELLIGENCE.md:13` says no official imagery was used, and V3 decision `V3_PRE_CODE_DECISION.md:49` says generated concept visuals were needed. Both conflict with the current V6 ledger `v6/ASSET_SOURCES.md:1-13,18-38`, which identifies current V6 files as direct official public media and gives their hashes. The supersession expressly does not establish transfer rights. No customer page, source document, asset or tool changed.

The one affected local run is [Lilux result](/Volumes/EXTERNAL/海外落地页/evidence/demo-workflow-20260905/lilux/runs/2026-09-06T13-51-58-930Z-6537394d/result.json), SHA-256 `e5f0f4ba1565d2a45de461d6cd6b3fdc57bf52bb4fe53514ca0f5aa68d74f114`, input `11be17f205537d429c7dad27945b8f36498c790012cb9c6112f7ceebeea42db1`: Mechanical FAIL, contract `595`, page `0`, external/independent `6`, reconciliation targets `195`. The external six remain offline/independent-review UNKNOWNs; no UNKNOWN was removed for a mechanical PASS. The remaining 595 contract findings show that Lilux’s current DOM-derived records still require individual source/asset/fact mapping.
