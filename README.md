# 拾光校园失物招领

免登录静态网站初步版本，适合先公开体验。

## 功能

- 浏览、搜索、分类筛选失物与招领线索
- 发布和管理线索
- 规则匹配可能相关的信息
- 本地站内消息（支持图片和撤回）
- 适配手机与桌面浏览器

## 发布到 GitHub Pages

1. 在 GitHub 新建一个 **Public** 空仓库，例如 `shiguang-campus`。创建时不要勾选添加 README、License 或 `.gitignore`。
2. 将本目录内的所有文件上传到仓库根目录，包括 `.github/workflows/pages.yml`。
3. 在仓库 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**。
4. 等待 **Actions** 页的 `Deploy static site` 工作流成功。网址格式为 `https://<GitHub用户名>.github.io/<仓库名>/`。

## 当前版本的数据范围

无需登录，任何打开网站的人都能浏览并使用页面。发布内容、消息和图片保存在各自浏览器的本地存储里，不会在不同用户、设备或浏览器之间同步；因此本版是公开可访问的体验站，不是共享数据库版。请勿填写手机号、身份证号、宿舍门牌等敏感信息。

