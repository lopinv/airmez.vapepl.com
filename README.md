# AiRMEZ — 品牌站产物（airmez.vapepl.com）

本目录是 AiRMEZ 品牌站（Cloudflare Pages 项目 `airmez-vapepl`）的静态构建产物，由 `bun run build` 生成，**请勿手改**——重新构建会整体重生成。

- 品牌：AiRMEZ（airmez.vapepl.com）
- 规模：4 个型号、47 个口味变体页
- 用途：信息/导购站，全部购买 CTA 带 UTM 指向 https://vapepl.com（所有成交在 vapepl.com 完成）
- 部署：`bun run deploy airmez`（wrangler 直传）或 `bun run package` 出 `dist/airmez-vapepl.zip` 拖入 CF 控制台上传

关键文件：`CNAME`（CF Pages 自定义域声明，内容为 `airmez.vapepl.com`）、`sitemap.xml`、`robots.txt`、`llms.txt`、`404.html`。
