**English** | [中文版](./CONTRIBUTING.zh-CN.md)

# Upload Guide

## Prepare your files

- Name your file `Topic_Name-or-Group.pptx`, for example `Digital-RMB_Group1.pptx`. Chinese filenames are also welcome.
- `.ppt` files are also accepted. An optional PDF with the same filename stem makes online preview easier.
- Browser uploads are limited to **25 MiB per file**. Compress images or remove embedded videos first. If the file is still too large, provide a download link in a pull request or issue for the maintainer to handle.
- Confirm that your materials are suitable for public sharing before uploading.

## Submit through the website

You only need a browser and a GitHub account. Installing Git is not required.

1. Open the [repository homepage](https://github.com/soxee1/fintech-course-ppts) and click **Fork → Create fork** to create a copy under your own account.
2. In **your own fork**, open `presentations`, choose **Add file → Upload files**, and drag in your slides and optional PDF.
3. Click **Commit changes**, enter a description such as `Add Digital RMB presentation, Group 1`, and save your upload.
4. Return to your fork's homepage and choose **Contribute → Open pull request**. Check that the base repository is `soxee1/fintech-course-ppts` and the base branch is `main`.
5. Click **Create pull request**, fill in the topic, presenter or group, date, and file path, then submit it for the maintainer to merge.

If you already have a fork, choose **Sync fork → Update branch** before your next submission to bring it up to date.

> Slides generally need to be downloaded and opened in PowerPoint, WPS, or Keynote. Open the file page and click **Download raw file**. PDFs can be previewed directly on GitHub.

## Collaborators with write access

Choose **Add file → Upload files** in the [presentations directory](https://github.com/soxee1/fintech-course-ppts/tree/main/presentations). You can create a branch and submit a pull request for the maintainer to review.

## Update the presentation index

You are welcome to update the [English index](./README.md#presentation-index) and [Chinese index](./README.zh-CN.md#presentation-index) in the same pull request. Alternatively, upload the files and provide the presentation details so the maintainer can add the entries.

Example index row: replace the date, topic, group, and filenames with your actual details. Use `—` if no PDF is available.

```markdown
| YYYY-MM-DD | Topic | Group X | [PPT](./presentations/Topic_GroupX.pptx) | [PDF](./presentations/Topic_GroupX.pdf) |
```

Replace spaces in paths with underscores, or encode them as `%20` in links.

## Updates and help

- To update a presentation, replace the existing file and submit the change. GitHub keeps previous versions in its history.
- To request a correction or removal, [open an issue](https://github.com/soxee1/fintech-course-ppts/issues/new) with the filename and details.
- If you do not have a GitHub account or need help uploading, contact the maintainer in the course group chat.

[Back to the homepage](./README.md)
