慈濟大學經營管理學系｜系所網站課堂專案
================================================

檔案結構
- index.html          系所簡介首頁（GitHub Pages 預設首頁）
- studentworks.html   學生作品展示頁
- graph/              本專案所有圖片素材（SVG）

上線前請確認
1. 本專案的文案、圖示與作品案例是課堂示範內容，不代表校方正式公告。
2. 正式發布前，請依老師要求確認系所名稱、課程、招生、師資、聯絡資訊及校方識別使用規範。
3. 將示範作品替換成實際作品，取得作者及照片中人物的授權，補上資料來源。
4. 請保持 index.html 小寫，且 index.html、studentworks.html、graph/ 位於同一層目錄。
5. 網站使用相對路徑，例如 graph/hero-campus.svg；不要改成電腦本機的絕對路徑。

GitHub Pages 發布步驟
1. 登入 GitHub，建立新的 Public repository。
2. 將本資料夾中的 index.html、studentworks.html、graph 資料夾與 README.txt 上傳至 repository 根目錄。
3. 進入 repository 的 Settings → Pages。
4. 在 Build and deployment 中選擇 Deploy from a branch。
5. Branch 選 main，資料夾選 /(root)，按 Save。
6. 等待 GitHub Pages 部署完成，網址通常為：
   - repository 名稱為 username.github.io 時：https://username.github.io/
   - 其他 repository 名稱時：https://username.github.io/repository-name/
7. 實際打開首頁和學生作品頁，點擊兩頁互相連結，並確認圖片正常顯示。

加分項目建議
- 將本 README 的 AI 協作說明保留在專案中，並在 studentworks.html 展示 AI 協作紀錄。
- 上架後使用 GitHub 網頁介面點開 index.html，點鉛筆圖示修改一段文字，再按 Commit changes，確認發布版本更新。
- 最後繳交真實 GitHub Pages 網址；網址必須以實際 repository 與部署結果為準，不能使用範例網址。


影音與加分專區（更新）
--------------------
- graph/department-intro.mp4：本專案使用 SVG 圖像製作的本地示範短片。
- graph/department-intro-poster.jpg：影片封面圖。
- 首頁和 studentworks.html 均已加入本地 video 標籤，使用 graph/ 相對路徑。
- studentworks.html 新增 AI 協作紀錄、GitHub 線上編輯與 Commit 實作步驟，以及媒體來源／授權紀錄。
- MEDIA_SOURCES.txt 記錄外部可用素材候選與授權來源。注意：外部來源頁尚未下載成專案素材；目前本地使用的是 graph/ 內的圖像及專案自製短片。

取得加分的最後操作
1. AI 協作紀錄：保存真實對話截圖，避免把整理摘要聲稱為逐字紀錄。
2. GitHub 版本控制：在自己已公開的 Repository 中線上修改 index.html 並 Commit changes。
3. 填妥 studentworks.html 的實際 Repository 網址、提交日期、Commit SHA、發布網址，並用截圖證明。未操作前請不要把狀態改成已完成。
