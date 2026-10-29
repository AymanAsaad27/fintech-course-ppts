[English](./CONTRIBUTING.md) | **中文版**

# 上传指南

## 准备文件

- 文件命名为 `汇报主题_姓名或组号.pptx`，例如 `数字人民币_第1组.pptx`。
- `.ppt` 格式也可以；建议另存一份同名 PDF，便于在线预览。
- 网页上传每个文件不能超过 **25 MiB**。大文件请先压缩图片或移除嵌入视频；仍然过大时，请在 Pull Request 或 Issue 中提供下载链接，联系维护者处理。
- 上传前确认资料适合公开分享。

## 通过网页提交

只需要浏览器和一个 GitHub 账号，不需要安装 Git。

1. 打开[资料库首页](https://github.com/soxee1/fintech-course-ppts)，点击右上角 **Fork → Create fork**，将仓库复制到自己的账号下。
2. 在**自己账号下的副本**中进入 `presentations`，点击 **Add file → Upload files**，拖入 PPT 和可选的 PDF。
3. 点击 **Commit changes**，填写说明，例如 `添加：数字人民币，第1组`，保存上传。
4. 回到自己的仓库首页，点击 **Contribute → Open pull request**。检查目标仓库为 `soxee1/fintech-course-ppts`，目标分支为 `main`。
5. 点击 **Create pull request**，填写主题、汇报人或小组、汇报日期和文件路径，提交后等待维护者合并。需要中文填写模板时，可以复制[中文提交模板](./.github/PULL_REQUEST_TEMPLATE.zh-CN.md)中的内容。

已有 Fork 的同学，提交新资料前先点击 **Sync fork → Update branch**，同步最新内容。

> PPT 文件通常需要下载后用 PowerPoint、WPS 或 Keynote 打开。进入文件页面，点击 **Download raw file** 下载。PDF 可以直接在 GitHub 预览。

## 已有写入权限的协作者

在[资料目录](https://github.com/soxee1/fintech-course-ppts/tree/main/presentations)中选择 **Add file → Upload files**。上传后可新建分支并提交 Pull Request，交由维护者统一收录。

## 更新汇报索引

欢迎在同一个 Pull Request 中更新[中文索引](./README.zh-CN.md#presentation-index)和[英文索引](./README.md#presentation-index)。也可以只上传文件并写清汇报信息，由维护者补充索引。

索引行示例，请替换为真实日期、主题、小组及文件名；没有 PDF 时填 `—`。

```markdown
| YYYY-MM-DD | 汇报主题 | 第X组 | [PPT](./presentations/主题_第X组.pptx) | [PDF](./presentations/主题_第X组.pdf) |
```

路径中的空格请改为下划线，或在链接中写成 `%20`。

## 更新与求助

- 更新汇报时，替换同名文件后重新提交，GitHub 会保留历史版本。
- 如需移除或更正资料，请[新建 Issue](https://github.com/soxee1/fintech-course-ppts/issues/new)，写清文件名和需要修改的内容。
- 没有 GitHub 账号或上传遇到问题的同学，可以在课程群联系维护者协助提交。

[返回中文首页](./README.zh-CN.md)
