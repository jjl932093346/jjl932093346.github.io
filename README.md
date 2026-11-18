# Jiliang Jian 的个人学术主页 | Jiliang Jian’s Academic Homepage

[访问主页 / Visit the homepage](https://jjl932093346.github.io/)

## 中文

这是 Jiliang Jian 的个人学术主页，包含个人简介、研究方向、教育经历、学术导师和联系方式。首页的正文和样式都在仓库根目录的 [`index.html`](index.html) 中。

### 修改页面内容

| 要更新的内容 | 在 `index.html` 中编辑 |
| --- | --- |
| 浏览器标签页标题 | `<head>` 内的 `<title>` |
| 姓名、身份、机构 | `<header>` 内的 `<h1>`、`.subtitle` 和机构段落 |
| 个人简介与研究方向 | `About Me` 的段落和 `Research Interests` 的列表。研究方向如有变化，请同步检查两处 |
| 教育经历和学术导师 | `Education` 和 `Academic Advisors` 下的列表项 |
| 联系邮箱 | `<header>` 和 `Contact` 中的邮箱链接。修改主邮箱时，同步更新两处显示文字和 `mailto:` 地址 |
| 页脚 | `.footer` 中的文字 |

### 调整页面样式

编辑 `<head>` 内的 `<style>`。用 `body` 调整字体、文字颜色、背景和行距，用 `.container` 调整正文宽度和留白，用 `h1`、`h2` 和 `a` 调整标题和链接。窄屏规则位于 `@media (max-width: 600px)`。保存后，用浏览器直接打开 `index.html`，检查桌面和手机宽度下的排版及邮箱链接。

### 旧模板文件

[`contents/`](contents/) 保留了旧模板的 Markdown 文件和 `config.yml`。新版首页不读取这些文件，也未引用旧的 [`static/js/scripts.js`](static/js/scripts.js)。修改这些文件不会更新首页。旧 Markdown 中的示例和占位内容未经核实，引用个人经历时请以已确认的资料为准。

### 部署与更新

1. 预览并检查 `index.html` 后，将更改推送或合并到 `main` 分支。
2. 在仓库的 [Actions](https://github.com/jjl932093346/jjl932093346.github.io/actions) 中检查对应提交的 Pages 构建和部署结果。[2026 年 11 月 17 日的部署记录](https://github.com/jjl932093346/jjl932093346.github.io/actions/runs/44072150189)显示，GitHub Pages 从 `main` 的仓库根目录构建并成功发布。
3. 部署成功后，打开[线上主页](https://jjl932093346.github.io/)确认更新。若未看到更改，先核对部署对应的提交，再刷新页面。若构建或部署失败，查看 Actions 日志，并在仓库的 **Settings → Pages** 中核对发布源。

### 署名与许可

本站早期版本基于 [Yixin Huang 的个人主页模板](https://github.com/Yixin0313/personal-homepage-template)（© 2025）。该模板改编自 [Sen Li 的学术主页模板](https://github.com/senli1073/senli1073.github.io)。仓库的 [`LICENSE`](LICENSE) 包含 MIT 许可证正文，版权声明中的姓名仍是占位符 `"Yourname"`。复用模板代码时，请保留适用的版权和许可声明。

## English

This is Jiliang Jian’s academic homepage. It covers his background, research interests, education, academic advisors, and contact information. The homepage content and styles live in [`index.html`](index.html) at the repository root.

### Edit the page content

| To update | Edit in `index.html` |
| --- | --- |
| Browser tab title | `<title>` inside `<head>` |
| Name, role, and affiliations | `<h1>`, `.subtitle`, and the affiliation paragraphs in `<header>` |
| Biography and research interests | The paragraphs under `About Me` and the list under `Research Interests`. Check both when research interests change |
| Education and academic advisors | The list items under `Education` and `Academic Advisors` |
| Email addresses | The links in `<header>` and `Contact`. For the primary address, update both the visible text and the `mailto:` target in both places |
| Footer | The text in `.footer` |

### Adjust the page styles

Edit the `<style>` block inside `<head>`. Use `body` for fonts, text color, background, and line height, `.container` for content width and spacing, and `h1`, `h2`, and `a` for headings and links. The `@media (max-width: 600px)` block controls narrow-screen adjustments. Open `index.html` directly in a browser to check the layout at desktop and mobile widths and test the email links.

### Legacy template files

[`contents/`](contents/) retains the previous template’s Markdown files and `config.yml`. The current homepage reads neither these files nor the old [`static/js/scripts.js`](static/js/scripts.js). Editing them has no effect on the homepage. The legacy Markdown contains examples and placeholders. Use verified information when documenting personal history.

### Deploy updates

1. Preview and check `index.html`, then push or merge the changes into `main`.
2. Check the Pages build and deployment for your commit in the repository’s [Actions](https://github.com/jjl932093346/jjl932093346.github.io/actions) tab. The [November 17, 2026 deployment](https://github.com/jjl932093346/jjl932093346.github.io/actions/runs/44072150189) built from the repository root on `main` and published successfully.
3. Once deployment succeeds, open the [live homepage](https://jjl932093346.github.io/) to verify the update. If the change is missing, check which commit was deployed and refresh the page. If the build or deployment fails, inspect the Actions logs and check the publishing source under **Settings → Pages**.

### Credits and license

An earlier version of this site used [Yixin Huang’s personal homepage template](https://github.com/Yixin0313/personal-homepage-template) (© 2025), which was adapted from [Sen Li’s academic homepage template](https://github.com/senli1073/senli1073.github.io). The repository’s [`LICENSE`](LICENSE) contains the MIT License text and still uses `"Yourname"` as a placeholder in its copyright notice. Retain applicable copyright and license notices when reusing template code.
