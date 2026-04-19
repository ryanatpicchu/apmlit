# Amplit Landing Site

Standalone one-page site for Meta App Review / Access Verification.

## 部署方式（完全免費，三選一）

### 方案 A：GitHub Pages（最簡單，建議）

1. 建立新的 public GitHub repo，例如 `amplit-site`
2. 把 `amplit-site/` 底下的檔案（`index.html` + `privacy.html`）放進 repo 根目錄
3. GitHub repo → Settings → Pages → Branch: `main` → `/` (root) → Save
4. 等 1-2 分鐘，網址變成：`https://<你的 github username>.github.io/amplit-site/`
5. 把這個網址貼到 Meta Access Verification 表單的「Website」欄位

### 方案 B：Cloudflare Pages（如果已有 Cloudflare 帳號）

1. Cloudflare Dashboard → Workers &amp; Pages → Create → Pages → Upload assets
2. 上傳 `amplit-site/` 整個資料夾
3. 自動分配 `amplit-site.pages.dev` 網址

### 方案 C：Vercel（如果已有 Vercel 帳號）

1. 把 `amplit-site/` 推到 GitHub repo
2. Vercel → New Project → Import → 選 repo → Deploy
3. 自動分配 `amplit-site.vercel.app` 網址

## 檔案清單

- `index.html` — 主要 landing page
- `privacy.html` — 隱私政策（待建立）
- `README.md` — 本文件
