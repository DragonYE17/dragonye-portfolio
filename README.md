# Dragon YE — portfolio

Static GitHub Pages site. Image-first framework for commercial CGI. Every frame is an empty placeholder (`Image coming soon` plus an aspect hint). No live case studies yet.

The page at `work/example.html` (**A8 PRO MAX — Launch KV**) is a labeled example template, not a published project.

English is primary. Chinese sits underneath as a secondary line.

## Pages

| Page | Path |
| --- | --- |
| Home | `index.html` |
| About | `about.html` |
| Contact | `contact.html` |
| Example case | `work/example.html` |

GitHub Pages serves this repo from the `main` branch root: <https://dragonye17.github.io/dragonye-portfolio/>. A pull request does not change that site until it is merged.

## 说明

图像优先的静态作品集框架。图片均为空占位。`work/example.html`（A8 PRO MAX — Launch KV）是示例模板，不是已发布案例。合并到 `main` 之前，线上站点不会变。

## Drop in an image

Put the file in `images/` and add it as the first child of the matching `figure`. The aspect class stays so the crop hint remains until you change it. The “Image coming soon” caption hides once `src` is set.

```html
<figure class="frame r-16x9">
  <img src="images/hero.jpg" alt="Describe the frame">
  <figcaption>
    <span class="slot-title">Image coming soon</span>
    <span class="slot-meta">16:9 · Hero</span>
  </figcaption>
</figure>
```

From `work/example.html`, paths start with `../`.

## Contact tokens

`[EMAIL]` and `[SOCIAL]` are literal placeholders. Search the repo and replace both when the real contact is ready.
