# joshocon.github.io

Personal website built with Jekyll, hosted on GitHub Pages.

## Setup

No build step needed — GitHub Pages builds Jekyll automatically.

1. Replace the contents of your repo with these files.
2. Add your photo as `photo.jpg` in the root.
3. Add your CV as `cv.pdf` in the root.
4. Push to `main`. GitHub will build and deploy in ~1 minute.

## Structure

```
_layouts/
  default.html     ← shared nav + styles (edit once, applies everywhere)
_config.yml        ← site settings
index.md           ← About page
research.md        ← Research page
cv.md              ← CV page (iframe + download)
photo.jpg          ← your photo (add this)
cv.pdf             ← your CV (add this)
KUMarks_Jayhawk.png ← KU logo (keep from old repo)
```

## Adding a new page

Create `newpage.md` in the root:

```markdown
---
layout: default
title: New Page
---

Your content here.
```

It will automatically appear — just add a nav link in `_layouts/default.html`.
