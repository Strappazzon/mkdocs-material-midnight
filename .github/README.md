<!-- markdownlint-disable-next-line MD041 -->
<div align="center">
  <img width="64" src="https://cdn.jsdelivr.net/npm/@svgmoji/twemoji@2.0.0/svg/1F311.svg" alt="Logo">
</div>

<div align="center">
  <strong>mkdocs-material-midnight</strong>
</div>

<p align="center">
  <em>A Material for MkDocs theme</em>
</p>

[![Badge](https://img.shields.io/badge/Material%20for%20MkDocs-%3E%3D%209.6-2094f3?style=for-the-badge&labelColor=4051b5&logo=materialformkdocs&logoColor=fff)](https://squidfunk.github.io/mkdocs-material/)  
[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme inspired by Discord and Reddit color palettes. For consistency, this theme will modify the default color scheme as well.

You can see how it looks [here](https://gkb.strappazzon.xyz) on my gaming Knowledge Base.

## Getting Started

To use this theme in your Material for MkDocs documentation:

1. Add this repository as a submodule

   ```sh
   git submodule add "https://github.com/Strappazzon/mkdocs-material-midnight"
   ```

2. Reference the stylesheet in your configuration

   ```yaml
   extra_css:
     - path/to/midnight.css
   ```

## Recommended Configuration

```yaml
theme:
  font:
    text: Montserrat
    code: Fira Code
  icon:
    admonition:
      bug: material/bug
      danger: material/close-octagon
      example: material/format-list-bulleted-square
      info: material/information-box
      note: material/pencil-box
      question: material/help-box
      tip: material/lightbulb
    annotation: material/pencil-box
    edit: material/text-box-edit
    view: octicons/markdown-16
```
