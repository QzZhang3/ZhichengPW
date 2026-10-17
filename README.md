# Zhicheng Zhang — Personal Website

Zhicheng Zhang 的个人学术主页，使用 Jekyll 构建。

## 本地预览

在本目录中执行：

```bash
bundle install
bash run_server.sh
```

然后打开 http://127.0.0.1:4000/Zhicheng.github.io/ 。停止服务按 Ctrl+C。
如果旧目录的预览服务仍在运行，先停止旧服务，再从本目录启动。

## 内容位置

- `_config.yml`：姓名、头像、所属机构、Google Scholar、ORCID 和发布地址。
- `_pages/about.md`：个人简介、教育经历、News、Academic Service 和联系方式。
- `_includes/publications-content.md`：论文、专利和软件著作权；首页与独立论文页共用。
- `_pages/honors.md`：荣誉奖励与获奖证书。
- `_pages/collaborators.md`：Faculty and Mentors。
- `_pages/projects.md`：项目经历。
- `_data/navigation.yml`：顶部导航。
- `images/`：页面实际使用的头像、学校图标、证书预览和 PDF。
- `_sass/_sidebar.scss`：头像尺寸和旋转角度。
- `assets/css/main.scss`：News 滚动框、论文列表、人物卡片和证书布局。
- `_includes/head/custom.html`：使用 UNSW 校徽的网页图标。

## GitHub Pages

当前仓库：https://github.com/QzZhang3/Zhicheng.github.io

发布网址：https://qzzhang3.github.io/Zhicheng.github.io/

`_config.yml` 已配置为：

```yaml
repository: "QzZhang3/Zhicheng.github.io"
url: "https://qzzhang3.github.io"
baseurl: "/Zhicheng.github.io"
```

将本目录的源文件上传到自己的仓库，并在 Settings → Pages 中选择
Deploy from a branch、main、/(root)。`_site/` 是本地构建产物，不需要上传。

## 模板与许可证

保留 AcadHomepage 模板的布局、字体及所需样式和图标库。
原始 MIT 许可证保存在 `LICENSE`，第三方库的声明保留在对应源码中。
此副本不包含原仓库的 Git 历史、远程仓库地址、原作者个人素材、示例文档或引用统计工作流。
