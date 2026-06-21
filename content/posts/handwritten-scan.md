---
title: "A handwritten scan"
date: 2026-06-20
draft: false
tags: ["scans"]
---

Some notes are handwritten. Drop the image file into the `static/` folder
(e.g. `static/images/example-note-scan.png`) and reference it from the note
with a leading slash — anything in `static/` is served from the site root:

![A scanned handwritten note](/images/example-note-scan.png)

That's the whole trick: `static/images/example-note-scan.png` on disk becomes
`/images/example-note-scan.png` in the page. Use PNG or JPG for scans.
