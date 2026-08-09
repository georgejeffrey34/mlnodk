安博体育官方娱乐【Q-——333307——】安博体育官方娱乐【 辋芷《888yx●vip》 】
安博体育官方娱乐【Q-——333307——】安博体育官方娱乐【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：GitHub Pages + Hexo 保姆级教程

今天想和大家聊聊如何用 GitHub Pages 和 Hexo 快速搭建一个免费的个人技术博客。无论你是编程新手还是资深开发者，拥有一个独立的写作空间，对于沉淀知识、打造个人品牌都很有帮助。

 为什么要选择这套方案？

- 完全免费：托管在GitHub上，无需购买服务器。
- 高度可定制：Hexo主题丰富，支持深度二次开发。
- 版本管理：所有文章都是Markdown文件，天然支持Git版本控制。
- 访问速度快：配合CDN加速，国内访问体验尚可。

 核心步骤拆解（Windows/macOS通用）

第一步：环境准备
安装 Node.js 和 Git 是前提。Node.js 建议下载LTS版本，避免兼容性问题。安装完成后打开终端（Terminal），输入 `node -v` 和 `git --version` 验证环境。

第二步：安装Hexo并初始化
全局安装Hexo命令行工具：
```bash
npm install -g hexo-cli
```
然后在目标目录初始化博客：
```bash
hexo init my-blog
cd my-blog
npm install
```
看到 `INFO  Start blogging!` 字样即表示成功。

第三步：本地预览
执行 `hexo s`，浏览器访问 `http://localhost:4000`，你会看到默认的主题页面。此时博客框架已经跑通了。

第四步：关联GitHub仓库
在GitHub上新建一个仓库，仓库名必须为 `你的用户名.github.io`。然后修改 `_config.yml` 文件中的deploy配置：
```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```
最后依次执行 `hexo g` 和 `hexo d` 部署上线。稍等片刻，访问 `你的用户名.github.io` 就能看到你的公开博客了。

 进阶优化建议

1. 更换主题：推荐 `Next` 或 `Fluid`，在GitHub搜索即可找到，文档完善，主题配置只需修改 `_config.yml`。
2. 绑定自定义域名：在仓库Settings的Pages设置里填写你的域名，并在DNS处添加CNAME解析。
3. 写作工作流：用 `hexo new post "文章标题"` 生成草稿，用Typora或VS Code写作，写完直接 `hexo d` 发布。

 遇到问题怎么办？

如果 `hexo d` 报错，多半是SSH key未配置或仓库权限问题。在GitHub添加SSH公钥即可解决。若预览样式丢失，清一下浏览器缓存或执行 `hexo clean` 后重新生成。

---

搭建博客最难的是坚持输出，工具只是起点。如果你在部署过程中卡住了，欢迎在评论区贴出报错信息，我看到会第一时间回复交流。写作是一场长跑，期待你的第一篇文章上线。

如果这篇文章对你有帮助，记得点赞收藏，方便日后查阅。你的支持是我继续分享技术干货的最大动力！

相关推荐：

https://github.com/collinsdaniel218/coqkfm/blob/main/%E5%A8%B1%E4%B9%90%E4%BA%A7%E4%B8%9A%E5%8A%A8%E6%80%81%EF%BC%9A%E5%AE%89%E5%8D%9A%E4%BD%93%E8%82%B2%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0_%E7%A5%A8%E5%92%90%E7%B0%A7%E9%99%85%E7%BA%A0VVVJD.md

<img src="https://i.postimg.cc/hPb6H33g/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(87).png" />

相关推荐：

https://github.com/collinsdaniel218/coqkfm/commit/851e9b00cb0a190dbe6bec23ad8c90fa40b4e52b

<img src="https://i.postimg.cc/hPKV3zqB/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(8).png" />
相关推荐：

https://github.com/burkemichael2/ljxymn/blob/main/2026%E6%9D%83%E5%A8%81%E5%A4%8D%E7%9B%98%EF%BC%9A%E5%AE%89%E5%8D%9A%E4%BD%93%E8%82%B2%E4%B8%BB%E7%AE%A1%E5%AE%98%E6%96%B9_%E5%9C%83%E5%8F%B5%E9%B2%81%E5%8D%9C%E8%94%B7ZZZAO.md

<img src="https://i.postimg.cc/qRPWTfTp/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(83).png" />
相关推荐：

https://github.com/burkemichael2/ljxymn/commit/c270e855098f1fd96b129e327e32c15ce078f060

<img src="https://i.postimg.cc/hPKV3zqB/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(8).png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
