# Scoop bucket

[Scoop](https://scoop.sh) bucket for [QuotaBubble](https://github.com/izzet/quotabubble), a floating desktop widget that shows AI coding tool usage quotas.

```powershell
scoop bucket add izzet https://github.com/izzet/scoop-bucket
scoop install izzet/quotabubble
```

Update with `scoop update quotabubble`.

The manifest in `bucket/` is kept current automatically: a scheduled workflow checks QuotaBubble's GitHub releases and updates the version and hash.
