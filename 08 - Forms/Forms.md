# HTML Forms

## Form Tag

```html
<form action="#" method="post">
```

- `action` specifies where form data is sent.
- `method` specifies how data is sent (`GET` or `POST`).

---

## Common Input Types

| Type | Purpose |
|------|---------|
| `text` | Text input |
| `email` | Email input |
| `password` | Password input |
| `number` | Numeric input |
| `date` | Date picker |
| `radio` | Single-choice option |
| `checkbox` | Multiple-choice option |
| `submit` | Submit button |
| `reset` | Reset button |

---

## Labels

```html
<label for="name">Name:</label>
<input type="text" id="name">
```

- The `for` attribute connects the label with the input's `id`.

---

## Fieldset

```html
<fieldset>
    <legend>Personal Information</legend>
</fieldset>
```

- Groups related form controls.

---

## Validation

```html
<input type="text" required>
```

- `required` makes the field mandatory.
- Other useful attributes: `min`, `max`, `minlength`, `maxlength`, `pattern`.

---

## Best Practices

- Always use `<label>` with form inputs.
- Use meaningful `name` attributes.
- Use validation attributes for better user experience.
- Group related fields with `<fieldset>` and `<legend>`.