# network / active

Mechanical: UNKNOWN; Client-showable: AWAITING INDEPENDENT REVIEW.

Input: a6554cb04237edbe8024c711f4b4ed0a2528b957ede38100300c48693a3a2c81

Resume is a local recheck, not a scheduler. 7 findings: contract 0; page 0; external/independent 7. Full detail is in result.json.

- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BROWSER_CHECK_BLOCKED [static] desktop: page.evaluate: Execution context was destroyed, most likely because of a navigation. → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN BROWSER_CHECK_BLOCKED [static] mobile: page.evaluate: Target page, context or browser has been closed
Browser logs:

<launching> /Applications/Google Chrome.app/Contents/MacOS/Google Chrome --disable-field-trial-config --disable-background-networking --disable-background-timer-throttling --disable-backgrounding-occluded-windows --disable-back-forward-cache --disable-breakpad --disable-client-side-phishing-detection --disable-component-extensions-with-background-pages --disable-component-update --no-default-browser-check --disable-default-apps --disable-dev-shm-usage --disable-edgeupdater --disable-extensions --disable-features=AvoidUnnecessaryBeforeUnloadCheckSync,BoundaryEventDispatchTracksNodeRemoval,DestroyProfileOnBrowserClose,DialMediaRouteProvider,GlobalMediaControls,HttpsUpgrades,LensOverlay,MediaRouter,PaintHolding,ThirdPartyStoragePartitioning,BlockOriginHeaderModificationOnRedirect,Translate,AutoDeElevate,OptimizationHints,msForceBrowserSignIn,msEdgeUpdateLaunchServicesPreferredVersion --enable-features=CDPScreenshotNewSurface --allow-pre-commit-input --disable-hang-monitor --disable-ipc-flooding-protection --disable-popup-blocking --disable-prompt-on-repost --disable-renderer-backgrounding --disable-updater-scheduler --force-color-profile=srgb --metrics-recording-only --no-first-run --password-store=basic --use-mock-keychain --no-service-autorun --export-tagged-pdf --disable-search-engine-choice-screen --unsafely-disable-devtools-self-xss-warnings --edge-skip-compat-layer-relaunch --disable-infobars --disable-search-engine-choice-screen --disable-sync --enable-unsafe-swiftshader --headless --hide-scrollbars --mute-audio --blink-settings=primaryHoverType=2,availableHoverTypes=2,primaryPointerType=4,availablePointerTypes=4 --no-sandbox --disable-background-networking --force-webrtc-ip-handling-policy=disable_non_proxied_udp --user-data-dir=/var/folders/1q/6mf7kw2j1z19q1f9dydq60wh0000gn/T/playwright_chromiumdev_profile-GbQ7UL --remote-debugging-pipe --no-startup-window
<launched> pid=77813
[pid=77813][err] Trying to load the allocator multiple times. This is *not* supported.
[pid=77813][err] [77818:664009:0905/231536.365640:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.365844:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.366008:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.366034:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.366104:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.366125:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.366183:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.366207:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.366280:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.366303:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77813:664007:0905/231536.527950:ERROR:base/process/process_mac.cc:53] task_policy_set TASK_CATEGORY_POLICY: (os/kern) invalid argument (4)
[pid=77813][err] [77813:664007:0905/231536.527968:ERROR:base/process/process_mac.cc:98] task_policy_set TASK_SUPPRESSION_POLICY: (os/kern) invalid argument (4)
[pid=77813][err] [77818:664009:0905/231536.591846:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.591903:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.592008:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.592034:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.592111:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.592160:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.592236:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.595385:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664009:0905/231536.595650:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813][err] [77818:664078:0905/231536.595684:ERROR:ui/display/mac/cv_display_link_mac.mm:195] CVDisplayLinkCreateWithCGDisplay failed. CVReturn: -6670
[pid=77813] <gracefully close start>
[pid=77813] <forcefully close>
[pid=77813] <kill>
[pid=77813] <will force kill> → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] desktop: fetch POST https://example.invalid/write; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] desktop: ping POST https://example.invalid/beacon; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] desktop: document GET https://example.invalid/navigate; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] mobile: fetch POST https://example.invalid/write; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW
- EXTERNAL/INDEPENDENT_REVIEW_UNKNOWN / UNKNOWN NETWORK_BLOCKED [static] mobile: ping POST https://example.invalid/beacon; destination behavior not verified → EXTERNAL_OR_INDEPENDENT_REVIEW

Next: Resolve the classed findings: contract reconciliation is not a page defect; only PAGE_RENDER DEFECT is a same-version page fix.
