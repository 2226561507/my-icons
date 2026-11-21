# My Icon

提供在线图标链接，供个人 NAS 设备显示使用。定期更新，新增图标见 `新上传的图标.txt`。禁止商用。

## 图标地址

打开页面点击图标即可复制地址，也可直接拼接：

- 图标直链前缀：`https://cdn.jsdelivr.net/gh/2226561507/my-icons@main/dist/icon/`
- 示例：`https://cdn.jsdelivr.net/gh/2226561507/my-icons@main/dist/icon/Moviepilot-A.png`

## 一键部署

两个平台都会自动执行 `npm install` + `npm run build`，产物目录为 `dist`。

[![使用 EdgeOne Makers 部署](https://cdnstatic.tencentcs.com/edgeone/pages/deploy.svg)](https://edgeone.ai/pages/new?repository-url=https%3A%2F%2Fgithub.com%2F2226561507%2Fmy-icons&output-directory=.%2Fdist&install-command=npm%20install&build-command=npm%20run%20build)

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/2226561507/my-icons)

在线预览（替换成你的部署地址）：https://siriling.github.io/my-icons/dist

## 使用

- 点击图标复制 URL，点击文字查看部署教程
- 打开 CDN 开关可切换为 CDN 链接

## 分类

Docker 容器 / 路由器 / 虚拟机 / 项目 / 其他

## 本地运行

```bash
npm install
npm run serve
```

## 新增图标

1. 把图片放进 `public/icon/`，文件名统一用小写 `.png`
2. 在 `public/db.json` 追加一条：`{ "name": "图标名", "sort": "docker", "course": "" }`
3. 重新构建

> 不要只改 `dist/`：构建会先清空它，只改那里的内容会被覆盖。
