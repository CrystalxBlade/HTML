# HTML Links

## Anchor Tag

```html
<a href="URL">Link Text</a>
```

Used to create hyperlinks.

---

## href Attribute

Specifies the destination of the link.

Example:

```html
<a href="https://www.google.com">Google</a>
```

---

## target Attribute

| Value | Meaning |
|--------|---------|
| `_self` | Opens in same tab (default) |
| `_blank` | Opens in new tab |

Example:

```html
<a href="https://youtube.com" target="_blank">
```

---

## Relative Link

Links to another file in your project.

```html
<a href="about.html">About</a>
```

---

## Absolute Link

Links to another website.

```html
<a href="https://www.google.com">Google</a>
```

---

## Email Link

```html
<a href="mailto:example@gmail.com">
```

---

## Phone Link

```html
<a href="tel:+911234567890">
```

---

## Image Link

Wrap an image inside an anchor tag.

```html
<a href="...">
    <img src="..." alt="">
</a>
```

---

## Bookmark Link

Jump to another section on the same page.

```html
<a href="#section1">
```

Target element:

```html
<h2 id="section1">
```