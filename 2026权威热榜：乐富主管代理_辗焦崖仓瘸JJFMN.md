乐富主管代理【Q-——333307——】乐富主管代理【 辋芷《888yx●vip》 】
乐富主管代理【Q-——333307——】乐富主管代理【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：GitHub Pages + Hexo 完整教程

如果你是一名开发者，想要搭建一个属于自己的技术博客，但不想花费服务器费用，也不想折腾复杂的后台系统，那么 GitHub Pages + Hexo 绝对是最佳选择。本文将手把手教你从零开始，搭建一个免费、高速、可自定义的静态博客。

 为什么选择 Hexo + GitHub Pages？

- 完全免费：托管在 GitHub 上，无需购买服务器。
- 极速访问：静态页面加载快，支持 CDN 加速。
- 版本管理：所有文章都是 Markdown 文件，天然支持 Git 版本控制。
- 主题丰富：社区拥有大量精美主题，一键切换。
- SEO 友好：静态页面易于搜索引擎收录，非常适合打造个人品牌。

 前置准备

在开始前，请确保你已完成以下工作：
1. 注册一个 GitHub 账号。
2. 安装 Node.js（建议 LTS 版本）。
3. 安装 Git 并配置好 SSH 密钥。

 第一步：安装 Hexo 并初始化项目

打开终端，执行以下命令全局安装 Hexo 脚手架：

```bash
npm install -g hexo-cli
```

然后初始化博客目录并安装依赖：

```bash
hexo init my-blog
cd my-blog
npm install
```

启动本地服务预览：

```bash
hexo server
```

浏览器访问 `http://localhost:4000`，你就能看到默认博客页面了。

 第二步：创建 GitHub 仓库并部署

1. 在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`（注意：这是固定格式）。
2. 在博客根目录下，安装 `hexo-deployer-git` 插件：

```bash
npm install hexo-deployer-git --save
```

3. 编辑博客根目录下的 `_config.yml` 文件，配置部署信息：

```yaml
deploy:
  type: git
  repo: git@github.com:你的用户名/你的用户名.github.io.git
  branch: master
```

4. 生成静态文件并部署：

```bash
hexo clean
hexo generate
hexo deploy
```

稍等片刻，访问 `https://你的用户名.github.io`，你的博客就上线了！

 第三步：发布第一篇技术文章

文章存放在 `source/_posts` 目录下，使用 Markdown 编写。创建新

```bash
hexo new post "我的第一篇技术博客"
```

打开生成的文件，填充内容。注意在头部添加文章信息：

```markdown
---
title: 我的第一篇技术博客
date: 2025-01-15 10:00:00
tags: [教程, 入门]
categories: 经验分享
---
```

写完保存后，执行 `hexo generate && hexo deploy` 即可发布。

 第四步：绑定独立域名并优化 SEO

如果你想使用自己的域名，可在仓库 Settings 中添加 CNAME 记录，上传 CNAME 文件到 `source` 目录即可。此外，推荐安装 SEO 插件：

```bash
npm install hexo-generator-seo-friendly-sitemap --save
```

并在配置中开启站点地图，方便百度、Google 快速收录你的文章。

 结语：持续输出，积累影响力

技术博客的核心在于持续输出有价值的内容。建议每周至少更新一篇深度文章，记录项目实战、踩坑复盘或源码解析。同时，将文章同步分发到掘金、CSDN、知乎专栏，引导流量回流至你的 GitHub 主页，打造完整的个人技术生态。

互动引导：如果你在搭建过程中遇到任何问题，欢迎在评论区留言，我会及时解答。也可以分享你搭建成功的链接，一起交流学习！

---

本文关键词：GitHub Pages、Hexo教程、个人博客搭建、静态博客、程序员建站、免费博客部署

相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/2026%E5%AE%98%E6%96%B9%E5%A4%8D%E7%9B%98%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E4%B8%BB%E7%AE%A1_%E8%AF%9C%E5%9F%A0%E6%BD%9C%E9%97%BB%E6%AE%96QJXRG.md

<img src="https://i.postimg.cc/sf6RVMFw/lefu-00017.png" />

相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/1c0bed8a749e26577d6031a5f5af60a6a89ce358

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/%E6%B2%89%E9%86%89%E6%96%87%E5%BF%83%E5%AF%BB%E6%A2%A6%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0_%E5%87%89%E8%B6%9F%E6%8B%BC%E4%B8%88%E9%9B%8DNUGUW.md

<img src="https://i.postimg.cc/XJx6BJpR/lefu-00011.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/commit/100102b91bd194dd059d254f5693b0987e06c3fb

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
