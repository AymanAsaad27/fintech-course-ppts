# 如何提交金科课汇报 PPT

## 先准备文件

- 文件名：`汇报主题_姓名或组号.pptx`，例如 `数字人民币_第1组.pptx`。
- `.ppt` 格式也可以；建议另存一份同名 PDF，方便同学在 GitHub 上预览。
- 网页上传每个文件不能超过 **25 MiB**。大文件可先压缩图片或移除嵌入视频；仍然过大时，请在 Pull Request 或 Issue 中提供下载链接，联系维护者处理。
- 上传前确认文件适合公开分享。

## 普通同学：通过网页提交

只需要浏览器和一个 GitHub 账号，不需要安装 Git。

1. 打开[资料库首页](https://github.com/yequanzhen02-maker/fintech-course-ppts)，点击右上角 **Fork → Create fork**，将仓库复制到自己的账号下。
2. 在**自己账号下的仓库副本**中打开 `presentations` 目录，点击 **Add file → Upload files**，拖入 PPT 和可选的 PDF。
3. 点击 **Commit changes**，填写说明，例如 `添加：数字人民币，第1组`，保存上传。
4. 回到自己仓库首页，点击 **Contribute → Open pull request**。检查目标仓库是 `yequanzhen02-maker/fintech-course-ppts`，目标分支是 `main`。
5. 点击 **Create pull request**，填写主题、汇报人或小组、汇报日期和文件路径。提交后等待维护者合并。

已有 Fork 的同学，提交新资料前先在自己的仓库点击 **Sync fork → Update branch**，同步资料库的最新内容。

> PPT 文件通常需要下载后用 PowerPoint、WPS 或 Keynote 打开。进入文件页面后，点击 **Download raw file** 下载。PDF 可以直接在 GitHub 预览。

## 已有写入权限的协作者

在[本仓库的资料目录](https://github.com/yequanzhen02-maker/fintech-course-ppts/tree/main/presentations)中选择 **Add file → Upload files**。上传后可选择新建分支并提交 Pull Request，交由维护者统一收录。

## 汇报索引

欢迎在同一个 Pull Request 中更新[首页索引](./README.md)。也可以只上传文件、写清汇报信息，由维护者补充索引。

索引行示例（替换为真实文件名和日期后使用，不保留示例内容）：

```markdown
| YYYY-MM-DD | 汇报主题 | 第X组 | [PPT](./presentations/主题_第X组.pptx) | [PDF](./presentations/主题_第X组.pdf) |
```

文件路径包含空格时，请将空格改为下划线，或在链接中写成 `%20`。

## 更新与求助

- 更新自己的汇报时，替换同名文件后重新提交，GitHub 会保留历史版本。
- 如需移除或更正资料，请[新建 Issue](https://github.com/yequanzhen02-maker/fintech-course-ppts/issues/new)，写清文件名和需要修改的内容。
- 没有 GitHub 账号或上传遇到问题的同学，可以在课程群联系维护者协助提交。
