# HTML Tables

## Table Tags

| Tag | Purpose |
|------|---------|
| `<table>` | Creates a table |
| `<tr>` | Table row |
| `<th>` | Table heading |
| `<td>` | Table data |
| `<thead>` | Table header section |
| `<tbody>` | Table body section |
| `<tfoot>` | Table footer section |

---

## Basic Table

```html
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Satish</td>
        <td>24</td>
    </tr>
</table>
```

---

## Rowspan

Merges cells vertically.

```html
<td rowspan="2">
```

---

## Colspan

Merges cells horizontally.

```html
<th colspan="3">
```

---

## Table Sections

- `<thead>` → Header
- `<tbody>` → Body
- `<tfoot>` → Footer

---

## Best Practices

- Use `<th>` for headings.
- Use `<thead>`, `<tbody>`, and `<tfoot>` for better structure.
- Avoid using the `border` attribute in real projects. CSS is the preferred way to style tables.