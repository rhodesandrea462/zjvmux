乐富主管官方【Q-——333307——】乐富主管官方【 辋芷《888yx●vip》 】
乐富主管官方【Q-——333307——】乐富主管官方【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕别人拥有独立博客？其实通过 GitHub Pages 和 Hexo，你可以在半小时内免费搭建一个高速、稳定的个人网站。本文将手把手带你完成从环境配置到一键部署的全流程，小白也能轻松上手。

 为什么选择 GitHub Pages + Hexo？

- 完全免费：无需购买服务器和域名
- 极速访问：依托 GitHub 全球 CDN，国内访问速度优秀
- 版本管理：所有文章基于 Git，历史记录清晰可回溯
- 生态丰富：Hexo 拥有超过 400+ 主题和插件

 环境准备（Windows/Mac 通用）

在开始前，请确保电脑已安装以下工具：

1. Node.js（建议 v18+）：[官方下载地址](https://nodejs.org/)
2. Git：用于代码提交和版本管理
3. GitHub 账号：国内用户推荐开启 Two-Factor Authentication

> 小提示：安装 Node.js 后，在终端输入 `node -v` 验证是否成功。

 五步搭建专属博客

 第一步：安装 Hexo 脚手架
```bash
npm install -g hexo-cli
```

 第二步：初始化博客项目
```bash
hexo init my-blog
cd my-blog
npm install
```

 第三步：本地预览效果
```bash
hexo server
```
浏览器访问 `http://localhost:4000`，即可看到默认博客界面。

 第四步：连接 GitHub 仓库
1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`
2. 修改根目录下的 `_config.yml` 文件：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

 第五步：一键部署上线
```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

访问 `你的用户名.github.io`，恭喜！你的专属博客已正式上线。

 进阶技巧：让博客更专业

- 更换主题：推荐 [Next](https://theme-next.js.org/) 或 [Fluid](https://github.com/fluid-dev/hexo-theme-fluid)，支持响应式设计
- 绑定域名：在仓库 Settings → Pages 中填写自定义域名，并在 DNS 服务商添加 CNAME 记录
- 文章加密：通过 `hexo-blog-encrypt` 插件保护私密内容
- SEO 优化：安装 `hexo-generator-seo-friendly-sitemap` 自动生成站点地图

 常见问题排查

| 问题现象 | 解决方案 |
|---------|----------|
| `deploy` 报错 | 检查 Git 是否已连接 GitHub（SSH 或 Token） |
| 图片无法显示 | 使用 `hexo-asset-img` 插件或图床 |
| 首页不刷新 | 强制清理浏览器缓存或使用无痕模式 |

 留言互动

搭建过程中遇到任何问题，欢迎在评论区留言，我会第一时间回复。如果你有更多实用技巧，也欢迎分享交流！

如果本文对你有帮助，点赞 + 收藏 支持一下吧，后续将为你带来更多关于自动化部署、性能优化的干货内容。

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E7%A7%91%E6%8A%80%E7%88%86%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%AE%98%E6%96%B9_%E5%B1%A5%E8%B4%B8%E8%B7%83%E9%A2%90%E6%8D%B6JPRTH.md

<img src="https://i.postimg.cc/TwTXPmYs/lefu-00010.png" />

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/d8fe8cf51f4b4ee33e3089a9ee370c4e566aa69c

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />
相关推荐：

https://github.com/vazquezdarin376/rowkxj/blob/main/%E6%95%B0%E5%AD%97%E6%96%87%E5%A8%B1%E5%8A%A8%E6%80%81%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E4%BB%A3%E7%90%86_%E8%AF%A5%E4%BA%A4%E8%80%98%E9%9A%99%E5%86%8DOICXX.md

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />
相关推荐：

https://github.com/vazquezdarin376/rowkxj/commit/4fae679c289fe2c951513d66b7ce0bd7680c158f

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
