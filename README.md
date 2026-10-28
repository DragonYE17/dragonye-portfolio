# Dragon YE — portfolio

Static GitHub Pages site. Image-first framework for commercial CGI. Every frame is an empty placeholder (`Image coming soon` plus an aspect hint). No live case studies yet.

Home is an image archive: a name lockup, then alternating wide and narrow rows (`Project 01`–`Project 08`). `work/example.html` is an example sequence — full-bleed hero, a thin title, then inset image bands. It is not a published project. Visible copy does not name a client, employer, or model.

Studio (`about.html`) and Contact are secondary. English is primary.

## Pages

| Page | Path |
| --- | --- |
| Archive | `index.html` |
| Studio | `about.html` |
| Contact | `contact.html` |
| Example sequence | `work/example.html` |

GitHub Pages serves this repo from the `main` branch root: <https://dragonye17.github.io/dragonye-portfolio/>. A pull request does not change that site until it is merged.

## 说明

首页是图像列表。`work/example.html`（Project 01）是示例图序，不是已发布案例。其余为 Project 02–08 空位。页面文案不出现客户、雇主或车型名称。合并到 `main` 之前，线上站点不会变。

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
