# Homeye landing page

Static site for https://jeromeliees.github.io/homeye-site/ — the app itself is not in this repository.

**别手改这个目录里的 HTML**：八个语言页由 `docs/marketing/build_site.py` 从
`docs/store/listing.md` 生成，改完跑一次脚本再推。两篇长文的正文在
`docs/marketing/pages/`，样式与落地页共用同一份 CSS（在生成器里）。
