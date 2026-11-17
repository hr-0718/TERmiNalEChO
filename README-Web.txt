HREngine Web Release

Local test: double-click StartLocal.bat, then click Start in the browser.
The local server is bound to 127.0.0.1 only. Close its window or press Ctrl+C to stop.
Do not open index.html directly using file://. A WebGPU-compatible browser and GPU
are required. Localhost is a secure browser context. Internet hosting must use HTTPS.

GitHub Pages: put this directory's distribution files at your publishing root.
Keep .nojekyll (it preserves _Credit), index.html, HREngine.js, HREngine.wasm,
Assets.pack, reports and _Credit. All runtime URLs are relative, so a repository
subdirectory URL works. The supplied .gitignore excludes the local test helpers.
This build uses single-threaded Wasm and requires no COOP/COEP custom headers.
Select the publishing branch/folder in GitHub Pages settings yourself.
No repository was created, made public or published by this build.

WebSizeReport.json contains measured file sizes and explicitly labelled estimates.
Hosting compression and decoded CPU/GPU memory may be unknown. Size warnings are
advisory, not guarantees about every browser, GPU or network.