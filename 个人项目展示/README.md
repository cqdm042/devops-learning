# 个人项目展示

## 春秋大梦（个人网站 · 开发中）

技术：
- Astro 静态站点
- HTML / CSS、少量 JavaScript
- Git / GitHub
- Cloudflare Pages、Cloudflare Workers（测速端点调用）

简介：
个人网站开发与 Cloudflare 云服务集成实践。网站为纯静态架构，包含主页和工具箱页面；工具箱提供 IP 查询、DNS 查询、Ping、测速等功能，其中 IP 查询集成公共 API，测速页面调用部署在 Cloudflare Workers 上的测速端点。工具箱线上入口尚未全部完成，项目仍在开发中。

说明：测速端点是部署在 Cloudflare Workers 上的服务，本项目实现前端集成调用，Worker 源码不在本仓库内。

## KVideo 视频聚合平台（春秋影视 · 历史项目 · 已停止维护）

技术：
- Next.js / React / TypeScript
- Git / GitHub（fork：cqdm042/KVideo）
- Cloudflare Pages（GitHub 集成自动部署）

简介：
基于开源项目 KVideo（MIT 许可证，上游作者 Kuek Hao Yang）进行部署与平台集成实践：将开源项目 fork 到自己的 GitHub 仓库，曾通过 GitHub 与 Cloudflare Pages 集成进行部署，并尝试后续 Worker 迁移和服务端功能验证。因持续更新维护成本较高，现已停止维护，原访问地址已失效。
