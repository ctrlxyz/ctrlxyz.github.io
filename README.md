# Control Engineering, Robotics and Intelligent Systems Website

这是一个可直接部署到 **GitHub Pages** 的研究室官网模板，适合展示：

- 研究方向
- 成员信息
- 论文成果
- 新闻动态
- 联系方式与招生信息

## 文件结构

- `index.html`: 页面结构
- `styles.css`: 页面样式
- `script.js`: 移动端菜单和滚动出现动画
- `.github/workflows/deploy.yml`: GitHub Pages 自动部署配置

## 本地修改

直接编辑以下内容即可：

- 页面标题、研究室名称：`index.html`
- 研究方向、成员、论文、新闻、联系方式：`index.html`
- 视觉风格和颜色：`styles.css`

## 部署到 GitHub Pages

1. 把这个项目推送到 GitHub 仓库。
2. 进入 GitHub 仓库的 `Settings` -> `Pages`。
3. 如果使用 GitHub Actions，保持默认即可，仓库中的工作流会自动部署。
4. 首次成功后，网站会出现在：

```text
https://<你的用户名>.github.io/<仓库名>/
```

如果仓库名是 `<你的用户名>.github.io`，则网址会是：

```text
https://<你的用户名>.github.io/
```

## 建议你下一步替换的内容

- `Control Engineering, Robotics and Intelligent Systems`
- `Professor Shenglin Mu`
- 所有邮箱、地址、学生姓名
- 论文标题和新闻占位内容

## 可扩展方向

- 增加英文页面
- 增加成员头像和项目页面
- 增加论文 PDF、代码和数据集链接
- 接入 Google Scholar / ORCID / GitHub 链接
