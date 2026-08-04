乐富官方客服【Q-——333307——】乐富官方客服【 辋芷《888yx●vip》 】
乐富官方客服【Q-——333307——】乐富官方客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是不是也想拥有一个属于自己的技术博客，却总是被服务器费用、域名备案、后台维护劝退？

别担心，今天这篇文章，我用 GitHub Pages + Hexo 帮你零成本搞定。不需要买服务器，不需要懂后端，全程可视化操作，跟着做就行。

 为什么强烈推荐这套方案？

- 免费托管：GitHub Pages 提供无限流量静态托管，永久免费
- 极致速度：配合 Cloudflare CDN 全球加速，国内访问也不卡
- 版本管理：所有文章都是 Markdown 文件，天然支持 Git 版本回滚
- 高自定义：主题丰富，从极简到炫酷任你挑，还能自己改代码

 三步上手实操

 第一步：创建 GitHub 仓库

登录你的 GitHub 账号，新建一个仓库，命名为 `你的用户名.github.io`。注意：这个命名是强制规则，必须完全匹配，否则无法启用 Pages 服务。

 第二步：本地安装 Hexo 环境

确保电脑已安装 Node.js（版本建议 14+）。打开终端执行：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

初始化成功后，本地运行 `hexo s` 就能在浏览器预览效果。

 第三步：部署到 GitHub

修改 `_config.yml` 文件中的部署配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后依次执行：

```bash
hexo clean
hexo g
hexo d
```

浏览器访问 `https://你的用户名.github.io`，看到页面就说明部署成功了。

 进阶优化建议

1. 绑定自定义域名：在仓库 Settings 的 Pages 选项中填入你的域名，并在 DNS 解析处添加 CNAME 记录指向 `你的用户名.github.io`。
2. 添加评论系统：推荐使用 Giscus（基于 GitHub Discussions），无需数据库，加载快且支持 Markdown。
3. SEO 优化：安装 `hexo-generator-seo-friendly-sitemap` 插件，并确保每篇文章都有独立的 title 和 description。

 结语

这套方案我已经用了三年，零成本、零维护，写作体验极佳。如果你在部署过程中遇到任何报错，或者想了解某个具体配置的细节，欢迎在评论区留言，我会逐一回复。

你的第一个技术博客，今天就搭起来吧！

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B3%A8%E5%86%8Capp_%E5%A3%AC%E6%A1%88%E5%92%8F%E9%B8%AD%E6%B6%8EBVCCK.md

<img src="https://i.postimg.cc/TwTXPmYs/lefu-00010.png" />

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/131062088c77534e08d42ba4a76b4d03680d18f7

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />
相关推荐：

https://github.com/rhodesandrea462/zjvmux/blob/main/2026%E6%9D%83%E5%A8%81%E6%94%BB%E7%95%A5%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E5%B9%B3%E5%8F%B0_%E4%BB%98%E9%84%99%E5%A4%9C%E7%A2%8C%E6%B0%B8BGNHA.md

<img src="https://i.postimg.cc/1XjxMj0W/lefu-00015.png" />
相关推荐：

https://github.com/rhodesandrea462/zjvmux/commit/c4156aa382ad61f48278a8d7861e7484c5469676

<img src="https://i.postimg.cc/wT1Y39gp/lefu-00019.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
