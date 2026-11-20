# 璨 · 鑽石行星

星球聯動角色「璨」（遲星 d／CHN-242）的互動網頁。

- `index.html`：3D 鑽石星球。可以戳他、拿別的星球跟他比較、切換深夜模式；按「♪ 主題曲」播放〈When the Stars Go Out〉，歌詞支援中英、英日、純英文。
- `player.html`：主題曲歌詞播放器，2D 星空版。
- `song.mp3`：主題曲音檔。

## 上架到 GitHub Pages

1. 在 GitHub 建立一個新的 repository（例如 `chan-planet`），設為 Public。
2. 把這個資料夾裡的所有檔案上傳到 repository 根目錄（包含 `.nojekyll`）。
3. 到 Settings → Pages，Source 選「Deploy from a branch」，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 等一到兩分鐘，網址會是 `https://你的帳號.github.io/chan-planet/`；歌詞播放器在 `/player.html`。

3D 星球用的 three.js 從 jsDelivr 載入，需要連網才能顯示。直接雙擊 `index.html` 在電腦上打開時，瀏覽器可能擋住音檔或模組，請用 GitHub Pages 的網址瀏覽。
