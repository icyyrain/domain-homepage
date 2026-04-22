# Domain Homepage

一个可部署到 Cloudflare Pages 的纯静态网页模板。

## 本地文件

- `index.html`: 页面内容
- `styles.css`: 页面样式

## Cloudflare Pages 部署

1. 将本目录推送到 GitHub 仓库。
2. 在 Cloudflare 控制台进入 Workers & Pages。
3. 创建 Pages 项目并连接该 GitHub 仓库。
4. 构建设置选择：
   - Framework preset: None
   - Build command: 留空
   - Build output directory: `/`
5. 部署完成后，在 Custom domains 绑定你的域名。
