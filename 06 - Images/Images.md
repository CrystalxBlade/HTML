# HTML Images

## Image Tag

```html
<img src="" alt="">
```

The `<img>` tag is used to display images.

---

## src Attribute

Specifies the image path.

```html
<img src="assets/photo.jpg">
```

---

## alt Attribute

Alternative text shown if the image cannot be loaded.

```html
<img src="photo.jpg" alt="Mountain">
```

---

## width and height

Sets the image size.

```html
<img src="photo.jpg" width="300" height="200">
```

---

## title Attribute

Displays a tooltip when the mouse hovers over the image.

```html
<img src="logo.png" title="Company Logo">
```

---

## Image as a Link

Wrap the image inside an anchor tag.

```html
<a href="https://www.google.com">
    <img src="photo.jpg" alt="Image">
</a>
```

---

## Common Image Formats

- JPG / JPEG
- PNG
- GIF
- SVG
- WebP

---

## Best Practices

- Always provide an `alt` attribute.
- Keep images inside an `assets` or `images` folder.
- Use meaningful file names like `profile.jpg` instead of `img1.jpg`.
- Resize images appropriately to improve page performance.