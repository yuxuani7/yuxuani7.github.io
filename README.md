HomePage

## 标签功能
- 在 `_posts/YYYY-MM-DD-title.md` 的 front matter 中添加 `tags`，例如：
  ```yaml
  tags:
    - demo
    - math
  ```
- 运行脚本一键生成/更新标签聚合页：
  ```bash
  python3 scripts/generate_tags.py
  ```
- 标签索引页：`blog/tags.html`；单个标签页位于 `blog/tag/<slug>.md`，模板在 `_layouts/tag.html`。

## 本地预览
- `bundle exec jekyll serve` 或运行 `./preview.sh`
