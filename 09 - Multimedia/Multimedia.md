# HTML Multimedia

## Multimedia Tags

| Tag | Purpose |
|------|---------|
| `<audio>` | Plays audio |
| `<video>` | Plays video |
| `<source>` | Specifies media source |
| `<iframe>` | Embeds another webpage or content |

---

## Audio

```html
<audio controls>
    <source src="song.mp3" type="audio/mpeg">
</audio>
```

Common attributes:

- `controls`
- `autoplay`
- `loop`
- `muted`

---

## Video

```html
<video width="500" controls>
    <source src="video.mp4" type="video/mp4">
</video>
```

Common attributes:

- `controls`
- `autoplay`
- `loop`
- `muted`
- `poster`

---

## iframe

Used to embed external content.

Examples:

- YouTube Videos
- Google Maps
- Other Websites (if allowed)

```html
<iframe src="URL"></iframe>
```

---

## Best Practices

- Always include the `<source>` tag inside `<audio>` and `<video>`.
- Provide fallback text for unsupported browsers.
- Store media files inside an `assets` folder.
- Use `loading="lazy"` for large iframes when appropriate.