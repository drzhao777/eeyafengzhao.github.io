# Academic Pages 学术网页搭建指南

## 第一步：Fork 模板仓库

1. 访问 https://github.com/academicpages/academicpages.github.io
2. 点击右上角 **Fork** 按钮
3. 在弹出窗口中，将仓库名改为 `你的GitHub用户名.github.io`
4. 点击 **Create fork**

## 第二步：启用 GitHub Pages

1. 进入你 Fork 的仓库
2. 点击 **Settings** → 左侧 **Pages**
3. Source 选择 **GitHub Actions**
4. 等待几分钟，访问 `https://你的用户名.github.io` 查看效果

## 第三步：修改配置文件

需要修改的核心文件（我已为你准备好示例内容）：

| 文件 | 作用 |
|------|------|
| `_config.yml` | 网站基本信息、个人资料 |
| `_pages/about.md` | 首页个人简介 |
| `_pages/cv.md` | 简历页面 |
| `_publications/` | 论文列表（每篇一个文件） |
| `_talks/` | 学术报告/会议 |
| `_teaching/` | 教学经历 |
| `_portfolio/` | 研究项目 |

## 第四步：上传照片

1. 准备一张正方形个人照片（建议 500x500 像素）
2. 命名为 `profile.png`
3. 上传到仓库的 `images/` 文件夹

## 修改方法

**方法一：在线编辑（推荐新手）**
- 在 GitHub 仓库中点击文件 → 点击铅笔图标编辑 → Commit 保存

**方法二：本地编辑**
```bash
git clone https://github.com/你的用户名/你的用户名.github.io.git
# 修改文件后
git add .
git commit -m "Update content"
git push
```

## 注意事项

- 每次修改后需等待 1-3 分钟网站才会更新
- 文件使用 Markdown 格式，YAML 头部信息很重要
- 日期格式必须是 `YYYY-MM-DD`
