
# 项目计划

## 已完成

- [x] 移除微信认证、公众号与赞赏码相关逻辑和展示信息
- [x] 移除顶部菜单、联系方式与社交链接
- [x] 修复 Cloudflare 部署依赖：将 Wrangler 声明为开发依赖
- [x] 确认 Cloudflare 构建与部署命令分别为 `npm run build:cf`、`npx wrangler deploy`
- [x] 删除触发 Cloudflare 自动选择 pnpm 的 `pnpm-lock.yaml`
- [x] 在 `package.json` 中声明 `npm@10.9.2`，统一使用 `package-lock.json`

## 待验证

- [ ] 在 Cloudflare 环境重新执行构建与部署
