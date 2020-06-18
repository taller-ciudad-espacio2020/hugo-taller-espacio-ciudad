---
title: 'Ejemplo Post 1'
date: 2020-06-17T19:30:08+10:00
draft: false
weight: 4
summary: Syntax highlighting and menus can be configured via `config.toml`.
---

Whisper is a minimal documentation theme built for Hugo. The design &amp; functionality is intentionally minimal.

## Quickstart

Copy or git clone this theme into the sites themes folder `mynewsite/themes`

```
hugo new site whisper
git clone https://github.com/jugglerx/hugo-whisper-theme.git
```

### Code Highlighting

Whisper uses Hugo's in-built code highlighting with a github style code highlighting theme. https://gohugo.io/content-management/syntax-highlighting/

You can insert code snippets in any markdown file by using standard code fences syntax ie:

```js
function myFunction() {
  var x = document.getElementById('myDIV');
  if (x.style.display === 'none') {
    x.style.display = 'block';
  } else {
    x.style.display = 'none';
  }
}
```
