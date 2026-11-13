# Demo workflow engineering — PMO task

Date: 2026-09-05; acceptance: 2026-09-06
Status: 已验收 — 流程工具 v1，仅限下述范围

## 本轮结果

- 已把客户资料与素材映射、双视口机械检查、同版本返修和可恢复证据绑定接入项目默认执行入口。资料整理、配置和普通返修由执行 Owner 承担，不要求用户手填 contract 或运行命令。
- 已修正验收问句极性、局部缺陷误触发整体重做、模板复用的过度限制；保留客户事实、独立视觉判断与原授权边界。
- 独立 Reviewer 已核对当前实现、规则、真实双视口证据和完整机器测试回执。12 tests / 12 pass / 0 fail；进程自然 exitCode 0。
- 三份既有客户页只读回放；Puggles 完成资料/selector 对齐，contract/page 缺陷均为 0，六项外部/独立核验限制仍保留。Washy 与 Lilux 的来源对齐待办不被视为客户页面缺陷。未改客户页面。
- 本次不证明客户视觉满意、购买意愿、远程地图/iframe 可用性、Client-showable、部署、发送、转让或无人值守；实际减少用户介入的幅度须由后续正常制作验证。

## 最终验收证据

- Reviewer: Anscombe / `01a071f2-7e27-70a1-a5c1-990ff2edd340`; final review turn `01a0742c-39ac-7600-ac5d-83b6c6be1177` accepted the scoped workflow tool.
- 原始 stdout: [test-run-20260906-session-20203.tap](test-run-20260906-session-20203.tap), SHA-256 `e81d63e1e77c5af07c43b7f18a978ec5dd4040c4e714c36a70d5172690c6d6ac`.
- 机器回执: [test-run-20260906-session-20203.receipt.json](test-run-20260906-session-20203.receipt.json), SHA-256 `d674ffdb360abfb7261db27029b90f9b39aecf85198ab537edd4d01d1e398320`; session 20203, natural exitCode 0, 95.418 seconds.
- 审定版本: core `3835c5ed4b4e697c68cb27c3fac20072b35097082db5281ac78137e89801d21e`; browser `053d4fc0004e6cc67be6ca3f934fb83ebf8778251b4b47c720d9cbda758eb2be`; cli `7346b822729975e77c7d13f96c48b3e10b66777779c4e94885460aa5b504130d`; test `390cf3f669cae253bbd3991c4141c0e21b8ba78372c2373ea3f8c1963fde9cbc`.
- `test-output-20260906.tap` 是历史转录摘要，不作为原始执行回执。

## User outcome

The user authorized implementation of the reviewed process improvements: “做，我只需要我的体验能够变好”. Reduce repeated requests to add customer material, repair ordinary layout/link defects, and resume stalled work. Do not represent scripts passing as proof of visual quality or purchase intent.

## Ownership and scope

- Implementation owner: Hegel / `01a071f1-3577-77a0-b510-101f0bcc3fb9`.
- Independent reviewer: Anscombe / `01a071f2-7e27-70a1-a5c1-990ff2edd340`.
- PMO: current project task; routing, evidence review, and reporting only.
- Project root: `/Volumes/EXTERNAL/海外落地页` (configured non-Git project).
- Implementation write scope: `tools/demo-workflow/`, this evidence directory except `PMO_TASK.md`, and related clauses in `AGENTS.md`, `PROJECT_CORE.md`, `REPLACEMENT_READY_DEMO_GATE_SOP.md`, `DEMO_CONTENT_ACTIVATION_TEMPLATE.md`.
- Existing customer pages and published/display packages remain read-only. Three historical customer cases are validation inputs, not new prospect or customer-demo acceptance.
- No global-rule edits, package installation, deployment, publication, email, forms submission, account access, purchase, deletion, or source transfer.
- Model settings are not inferred from project rules. No new high-effort or paid service escalation is authorized by this task.

## Minimum result

1. Consistent acceptance wording and repair-versus-redesign routing.
2. One structured customer/material/action contract using existing project facts and source classifications.
3. A runnable check entry point with static checks and real desktop/mobile evidence.
4. Version-bound evidence and resumable local job state. Resume is not an unattended scheduler.
5. Red/green defect tests and read-only replay of three existing customer cases.
6. Existing project instructions point to the runnable workflow; ordinary in-scope repair does not require another user confirmation.

## Required evidence and acceptance owners

| Layer | Owner | Evidence |
| --- | --- | --- |
| Rules and implementation | Implementation owner | Exact changed files and original-to-final diff or before/after evidence |
| Mechanical checks | Implementation owner | Command, current input/version hashes, raw test output, intentional failure and corrected result |
| Browser | Implementation owner | Real 1440×900 and 390×844 render evidence, page/asset binding, precise unsupported cases |
| Independent review | Independent reviewer | Code and original evidence review; concrete findings; no author self-PASS substitution |
| PMO | Current task | Review of the above and a scoped final conclusion |
| User experience | Future normal use/user | Intervention count, first-pass independent acceptance, total rework and cost; not yet established by a tool release |

## Proportional risk review

Necessary conditions are consistent inputs, reliable defect detection, independent visual judgment, and resumable ownership. Additional approval layers are not the objective. This change affects multiple future execution owners but remains local and reversible. Main counterexamples are a hidden element counted as coverage, stale evidence accepted after a file change, EXCLUDE used to erase missing work, an owner-authored review counted as independent, or a workflow PASS mistaken for deployment/customer-demo acceptance. Independent review must specifically check these cases. Existing product, source-use, external-action, and final-transfer boundaries must remain intact.

## Next acceptance entry

This workflow-tool acceptance chain is closed for the version above. Apply the existing default entry point to future specifically authorized Demo work; customer visual/external/Client-showable decisions remain separate. No automatic downstream deployment, outreach or new customer work is initiated by this closure.

### Current acceptance checkpoint

Closed on 2026-09-06. Independent review accepted the Hero coordinate fix, sibling-overlay behavior, reciprocal source mapping, confirmed-mapping failure routing, current instructions and original test receipt. The missing original receipt was replaced by one captured run of the unchanged existing suite; no new tests, code edits or customer replays were added for that capture. No mandatory workflow-tool acceptance item remains open.

## Execution continuation

The initial implementation turn stopped with `Selected model is at capacity. Please try a different model.` This is a service-capacity error, not a failed customer case or lost implementation. The same owner task was resumed with requested model `gpt-5.6-terra`, reasoning `medium`, following the project's ordinary-execution route. A second read of the actual runtime model is unavailable here: runtime model remains UNKNOWN rather than being inferred from the request. Local reversible implementation and validation continue within the original scope. No new customer task, publication, or package installation was authorized.
