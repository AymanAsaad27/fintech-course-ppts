# 上传指南 | Upload Guide

## 准备文件 / Prepare your files

- 文件命名为 `汇报主题_姓名或组号.pptx`，例如 `数字人民币_第1组.pptx`。<br>
  Name your file `Topic_Name-or-Group.pptx`, for example `Digital-RMB_Group1.pptx`. Chinese filenames are also welcome.
- `.ppt` 格式也可以；建议另存一份同名 PDF，便于在线预览。<br>
  `.ppt` files are also accepted. An optional PDF with the same filename stem makes online preview easier.
- 网页上传每个文件不能超过 **25 MiB**。大文件请先压缩图片或移除嵌入视频；仍然过大时，请在 Pull Request 或 Issue 中提供下载链接，联系维护者处理。<br>
  Browser uploads are limited to **25 MiB per file**. Compress images or remove embedded videos first. If the file is still too large, provide a download link in a pull request or issue for the maintainer to handle.
- 上传前确认资料适合公开分享。<br>
  Confirm that your materials are suitable for public sharing before uploading.

## 通过网页提交 / Submit through the website

只需要浏览器和一个 GitHub 账号，不需要安装 Git。<br>
You only need a browser and a GitHub account. Installing Git is not required.

1. 打开[资料库首页](https://github.com/soxee1/fintech-course-ppts)，点击右上角 **Fork → Create fork**，将仓库复制到自己的账号下。<br>
   Open the [repository homepage](https://github.com/soxee1/fintech-course-ppts) and click **Fork → Create fork** to create a copy under your own account.
2. 在**自己账号下的副本**中进入 `presentations`，点击 **Add file → Upload files**，拖入 PPT 和可选的 PDF。<br>
   In **your own fork**, open `presentations`, choose **Add file → Upload files**, and drag in your slides and optional PDF.
3. 点击 **Commit changes**，填写说明，例如 `添加：数字人民币，第1组`，保存上传。<br>
   Click **Commit changes**, enter a description such as `Add Digital RMB presentation, Group 1`, and save your upload.
4. 回到自己的仓库首页，点击 **Contribute → Open pull request**。检查目标仓库为 `soxee1/fintech-course-ppts`，目标分支为 `main`。<br>
   Return to your fork's homepage and choose **Contribute → Open pull request**. Check that the base repository is `soxee1/fintech-course-ppts` and the base branch is `main`.
5. 点击 **Create pull request**，填写主题、汇报人或小组、汇报日期和文件路径，提交后等待维护者合并。<br>
   Click **Create pull request**, fill in the topic, presenter or group, date, and file path, then submit it for the maintainer to merge.

已有 Fork 的同学，提交新资料前先点击 **Sync fork → Update branch**，同步最新内容。<br>
If you already have a fork, choose **Sync fork → Update branch** before your next submission to bring it up to date.

> PPT 文件通常需要下载后用 PowerPoint、WPS 或 Keynote 打开。进入文件页面，点击 **Download raw file** 下载。PDF 可以直接在 GitHub 预览。<br>
> Slides generally need to be downloaded and opened in PowerPoint, WPS, or Keynote. Open the file page and click **Download raw file**. PDFs can be previewed directly on GitHub.

## 已有写入权限的协作者 / Collaborators with write access

在[资料目录](https://github.com/soxee1/fintech-course-ppts/tree/main/presentations)中选择 **Add file → Upload files**。上传后可新建分支并提交 Pull Request，交由维护者统一收录。<br>
Choose **Add file → Upload files** in the [presentations directory](https://github.com/soxee1/fintech-course-ppts/tree/main/presentations). You can create a branch and submit a pull request for the maintainer to review.

## 更新汇报索引 / Update the presentation index

欢迎在同一个 Pull Request 中更新[首页索引](./README.md#presentation-index)。也可以只上传文件并写清汇报信息，由维护者补充索引。<br>
You are welcome to update the [homepage index](./README.md#presentation-index) in the same pull request. Alternatively, upload the files and provide the presentation details so the maintainer can add the entry.

索引行示例，请替换为真实日期、主题、小组及文件名；没有 PDF 时填 `—`。<br>
Example index row: replace the date, topic, group, and filenames with your actual details. Use `—` if no PDF is available.

```markdown
| YYYY-MM-DD | 汇报主题 / Topic | 第X组 / Group X | [PPT](./presentations/Topic_GroupX.pptx) | [PDF](./presentations/Topic_GroupX.pdf) |
```

路径中的空格请改为下划线，或在链接中写成 `%20`。<br>
Replace spaces in paths with underscores, or encode them as `%20` in links.

## 更新与求助 / Updates and help

- 更新汇报时，替换同名文件后重新提交，GitHub 会保留历史版本。<br>
  To update a presentation, replace the existing file and submit the change. GitHub keeps previous versions in its history.
- 如需移除或更正资料，请[新建 Issue](https://github.com/soxee1/fintech-course-ppts/issues/new)，写清文件名和需要修改的内容。<br>
  To request a correction or removal, [open an issue](https://github.com/soxee1/fintech-course-ppts/issues/new) with the filename and details.
- 没有 GitHub 账号或上传遇到问题的同学，可以在课程群联系维护者协助提交。<br>
  If you do not have a GitHub account or need help uploading, contact the maintainer in the course group chat.
