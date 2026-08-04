乐富主管下载【Q-——333307——】乐富主管下载【 辋芷《888yx●vip》 】
乐富主管下载【Q-——333307——】乐富主管下载【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 保姆级教程

今天翻到三年前的第一篇博客，突然觉得当初咬牙折腾 GitHub Pages 真的太值了。如果你也想拥有一个完全属于自己的技术小窝，这篇教程就是为你准备的——全程免费，不用买服务器，甚至不用懂 Docker。

 为什么推荐 Hugo 而非 Hexo？

我最初用过 Hexo，但 Node.js 依赖树实在让人头大。Hugo 是 Go 写的单二进制文件，解压就能跑，本地预览秒开。如果你是追求极致速度的开发者，或者受够了 Node 版本地狱，Hugo 绝对是首选——生成 1000 篇文章的静态站点，用时不到 1 秒。

 三步部署，GitHub Actions 全自动

 第一步：本地初始化

```bash
brew install hugo   macOS
hugo new site my-blog && cd my-blog
git init && git remote add origin git@github.com:用户名/仓库名.git
```

 第二步：选择主题与关键词布局

强烈推荐 LoveIt 或 LeaveIt 主题（Star 数均过千）。百度对清晰导航和内链结构有偏好，记得在 `config.toml` 里开启面包屑导航和标签页，这样爬虫能更快抓取你的“技术博客”相关内容。

 第三步：GitHub Actions 自动部署

在仓库里新建 `.github/workflows/deploy.yml`，填入官方 action 模板。每次 `git push` 后，Actions 会自动帮你构建并推送静态文件到 `gh-pages` 分支，无需手动操作。

 常见坑与避坑指南

- 域名绑定：在仓库 Settings → Pages 里填自定义域名，并在 DNS 加 CNAME 记录，记得等 SSL 证书签发（约 10 分钟）。
- 图片懒加载：主题默认开启，但需要把图片放在 `static/images` 下，路径写相对地址。

 互动引导

部署成功后，你的站点域名就是 `用户名.github.io`。如果卡在某一步，评论区贴出报错信息，我看到后第一时间帮你排查。觉得有用的话，点个 Star 支持一下，后续会更新“如何用 Hugo 写技术笔记”的进阶玩法。

---

本文覆盖关键词：GitHub Pages 教程、Hugo 部署、静态博客搭建、GitHub Actions 自动化、免费个人网站。欢迎转载，请保留出处。

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E7%A7%91%E6%8A%80%E7%83%AD%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E5%AE%A2%E6%9C%8D_%E6%93%9E%E6%A1%A5%E7%96%97%E5%AE%A2%E7%A8%8DLLLLT.md

<img src="https://i.postimg.cc/xTBDzB1n/lefu-00020.png" />

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/3aa17f9f4caef5cf28fd33a5d19fe939e0f3be00

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />
相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E6%9D%83%E5%A8%81%E5%B9%B2%E8%B4%A7%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86_%E7%96%B5%E6%A4%8E%E5%9C%B0%E9%9F%B6%E8%80%99NOUVD.md

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />
相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/1adf80c37a658ccc7aa9c6b7f39b96d5d9244154

<img src="https://i.postimg.cc/c4vG6dZ5/lefu-00018.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
