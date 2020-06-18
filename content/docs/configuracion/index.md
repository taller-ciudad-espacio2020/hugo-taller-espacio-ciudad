---
title: 'Configuración'
date: 2020-06-17T19:30:08+10:00
draft: false
weight: 3
summary: Syntax highlighting and menus can be configured via `config.toml`.
---

<!-- Contenido del Post -->

## Syntax Highlighting

Whisper uses the in-built code highlighting that ships with hugo. https://gohugo.io/content-management/syntax-highlighting/

You can insert code snippets in any markdown file by using standard code fences syntax ie:

````
```
insert code here
```
````

You can specify the langauge by adding a declaration after the backticks

````
```javascript
insert code here
```
````

### Pygments Options

The following code highlighting options are configured in the `config.toml`

```toml
pygmentsCodeFences = true
pygmentsCodefencesGuessSyntax = true
pygmentsUseClasses = true
```

## Main menu

Configure the main menu by editing the `config.toml`

```toml
[[menu.main]]
name = "Inicio"
url = "/"
weight = 1

[[menu.main]]
name = "Documentación"
url = "/docs/"
weight = 2
```
