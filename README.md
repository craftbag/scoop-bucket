# craftbag Scoop bucket

```powershell
scoop bucket add craftbag https://github.com/craftbag/scoop-bucket
scoop install craftbag/craftbag
```

Each GitHub Release of [craftbag/craftbag](https://github.com/craftbag/craftbag) rewrites `bucket/craftbag.json`. The committed JSON is the source of truth. Client-side `checkver` is a fallback only.
