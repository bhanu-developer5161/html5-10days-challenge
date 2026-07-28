# Day 5 - Advanced HTML Forms

## What are Advanced HTML Forms?

Advanced HTML Forms use HTML5 input types and validation attributes to collect accurate data from users without using JavaScript.

---

# 1. HTML5 Input Types

## `<input type="number">`

**Meaning:**  
Used to accept only numbers.

**Attributes:**
- `min` → Minimum allowed value.
- `max` → Maximum allowed value.

Example:

```html
<input type="number" min="18" max="60">
```

---

## `<input type="date">`

**Meaning:**  
Creates a date picker.

Used for:
- Date of Birth
- Booking Date

Example:

```html
<input type="date">
```

---

## `<input type="time">`

**Meaning:**  
Allows users to select time.

Example:

```html
<input type="time">
```

---

## `<input type="color">`

**Meaning:**  
Creates a color selection box.

Example:

```html
<input type="color">
```

---

## `<input type="range">`

**Meaning:**  
Creates a slider to select a value.

Attributes:
- `min` → Minimum value.
- `max` → Maximum value.

Example:

```html
<input type="range" min="0" max="10">
```

---

# 2. Form Validation Attributes

## `required`

**Meaning:**  
Makes a field compulsory. User cannot submit an empty field.

Example:

```html
<input type="text" required>
```

---

## `placeholder`

**Meaning:**  
Displays a hint inside an input box.

Example:

```html
<input type="text" placeholder="Enter name">
```

---

## `minlength`

**Meaning:**  
Sets minimum number of characters.

Example:

```html
<input type="password" minlength="8">
```

---

## `maxlength`

**Meaning:**  
Sets maximum number of characters.

Example:

```html
<input type="text" maxlength="20">
```

---

## `min`

**Meaning:**  
Sets minimum number value.

Example:

```html
<input type="number" min="18">
```

---

## `max`

**Meaning:**  
Sets maximum number value.

Example:

```html
<input type="number" max="60">
```

---

## `pattern`

**Meaning:**  
Defines a specific format that input must follow.

Example:

```html
<input type="tel" pattern="[0-9]{10}">
```

Accepts:
```
9876543210
```

---

## `autocomplete`

**Meaning:**  
Allows the browser to suggest previously entered values.

Example:

```html
<input type="email" autocomplete="on">
```

---

# 3. Form Attributes

## `action`

**Meaning:**  
Specifies where form data is sent.

Example:

```html
<form action="/submit">
```

---

## `method`

**Meaning:**  
Defines how data is sent.

Types:

### GET
- Data is visible in URL.
- Used for search forms.

### POST
- Data is hidden.
- Used for registration/login forms.

Example:

```html
<form method="post">
```

---

# 4. Button Types

## Submit Button

**Meaning:**  
Sends form data.

Example:

```html
<input type="submit" value="Register">
```

---

## Reset Button

**Meaning:**  
Clears all entered form data.

Example:

```html
<input type="reset" value="Clear">
```

---

# 5. Important Difference

## `id` vs `name`

### id
- Identifies an element in HTML.
- Connects with `<label>`.

Example:

```html
<label for="email">Email</label>
<input id="email">
```

### name
- Identifies data when submitting the form.

Example:

```html
<input name="email">
```

---

# Day 5 Project Completed

Created:

✅ Advanced Registration Form  
✅ HTML5 Input Types  
✅ Form Validation  
✅ Field Grouping  
✅ Submit and Reset Buttons  

---

# Key Learning

HTML5 forms help create user-friendly forms with built-in validation without JavaScript.