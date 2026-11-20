# ScrollsExt

Owner board library for [Scrolls](https://github.com/vittorioapi91/Scrolls).

## Layout (required)

Every board is a **folder**, never a single nested JSON file:

```text
boards/{board_name}/{board_name}.json
boards/{board_name}/widgets/{widget_name}.json
```

- `{board_name}.json` — board shell (`widgets` is always `[]`; order listed in `widgetFiles`)
- `widgets/*.json` — one full widget object per file

Single-file packages (board + nested widgets in one JSON) are **not** supported.
