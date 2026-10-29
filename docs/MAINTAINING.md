**English** | [中文版](./维护说明.md)

# Maintainer Guide

## Add a presentation

1. Open **Pull requests** to review the submitted files and presentation details.
2. Check that the files can be downloaded, are clearly named, and are suitable for public sharing, then merge the submission.
3. Update the indexes in `README.md` and `README.zh-CN.md` with the date, topic, presenter or group, and file links. Use `—` when no PDF is available.
4. After adding the first presentation, remove the placeholder index rows and the empty-directory notices in `presentations/README.md` and `presentations/README.zh-CN.md`.

## Common tasks

- **Update files**: Replace the existing file and commit the change instead of adding multiple files named “final”.
- **Invite collaborators**: Invite users through **Settings → Collaborators**. Other students can contribute through forks and pull requests without an invitation.
- **Handle large files**: Compress images or remove embedded videos first. If an external download link is necessary, include the link and its expiration date in both indexes.
- **Maintain language versions**: English is the default. Keep each page's Chinese counterpart and the language links at the top in sync when editing navigation or guidance.

## Message for the course group

```text
Our FinTech course presentation repository is ready:
https://github.com/soxee1/fintech-course-ppts

The homepage is in English by default. Use the language link at the top to switch to Chinese.

Please contribute your presentation slides so everyone can browse and download them. Use the filename Topic_Name-or-Group.pptx. An accompanying PDF is welcome for online preview.

Follow the Upload guide linked on the homepage to submit through your browser. No Git installation is needed. If you need help uploading, contact me in the course group chat.
```

[Back to the course wiki](./Home.md)
