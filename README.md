# drawing-preview

Minimal, control-free preview of a PDF (page 1) or image, for Glide Web Embed components.

```
https://veenu-wootz.github.io/drawing-preview/?url=<file url>
```

Works with Glide storage and S3/AWS URLs. PDFs need the file host to allow CORS.

Optional params:
- `scheme=dark|light` – match the app theme so the embed stays transparent (Chrome paints it white on a mismatch)
- `align=center` – centre the drawing vertically (default: top)
- `page=2`, `bg=white`, `type=pdf|image` (when the URL has no file extension)
