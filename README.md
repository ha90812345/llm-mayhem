# App Store 網站（GitHub Pages）

AI模型大亂鬥 / LARGE LANGUAGE MAYHEM iOS 版的公開頁面：`index.html`（首頁）、`privacy.html`（隱私政策）、`support.html`（支援）、`terms.html`（使用條款）。中英同頁：英文在 `#en`。純靜態、沒有 JavaScript、沒有 Cookie、不載入外部資源。

發佈方式與網址見 `Docs/launch/ios/UPLOAD_NOW.zh-TW.md` 第 2 節。App 內「設定 › 隱私政策」開的是 `https://ha90812345.github.io/llm-mayhem/privacy.html`（`Config/GloryOnline.ini` 的 StorePrivacyUrl），所以 GitHub repo 名稱要叫 `llm-mayhem`；換網址要改那一行並重新打包。

`Tools/ios/package_appstore.sh` 不會發佈這個資料夾；`Deliverables/appstore/site/` 是它的複本。
