Amazing Postnatal Care 网站 — 使用说明
========================================

【本地打开】
解压后双击 index.html 即可在电脑或手机浏览器打开。
右上角 EN / 中文 按钮可即时切换语言。

【上线到 Vercel（最简单，不经过 GitHub）】
1. 打开 https://vercel.com/new
2. 选择 “Deploy” 下方的上传方式，或安装 Vercel CLI 后在本文件夹运行：  npx vercel --prod
3. 设置：Framework = Other，Build Command 留空，Output Directory 留空

【上线到 GitHub + Vercel】
1. 解压后，把本文件夹「里面的所有内容」放到仓库最外层
   （仓库首页应直接看到 index.html、assets/、_ds/ …，而不是一个文件夹）
2. 建议用 GitHub Desktop 一次提交；网页拖拽每次最多 100 个文件
3. Vercel → Settings → Root Directory 留空，Framework = Other，Build / Output 留空
4. Deployments → Redeploy

【检查】
assets/ 应有 171 个文件；_ds/fonts/ 内有字体文件。
sitemap.xml 里的 REPLACE-WITH-YOUR-DOMAIN.com 请换成正式域名。
