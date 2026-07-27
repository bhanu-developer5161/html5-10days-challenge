# 📚 Day 4 – HTML Forms

## Objective

Learn how to create HTML forms to collect user information.

---

# What is a Form?

An HTML form is used to collect data from users.

Examples:

* Login Form
* Registration Form
* Contact Form
* College Admission Form
* Job Application Form

---

# `<form>` Tag

The `<form>` tag creates a form.

**Syntax:**

```html
<form>

</form>
```

---

# Attributes of `<form>`

## action

Specifies where the form data is sent.

```html
<form action="submit.html">
```

---

## method

Specifies how data is sent.

```html
<form method="get">
```

or

```html
<form method="post">
```

### Difference

* **GET** → Data is visible in the URL.
* **POST** → Data is sent securely in the request body.

---

# `<label>` Tag

Provides a label for an input field.

**Example:**

```html
<label for="name">Full Name:</label>
```

---

# `<input>` Tag

Used to accept user input.

**Syntax:**

```html
<input type="text">
```

---

# Common Input Types

## Text

```html
<input type="text">
```

Used for names and usernames.

---

## Email

```html
<input type="email">
```

Accepts email addresses.

---

## Password

```html
<input type="password">
```

Hides typed characters.

---

## Number

```html
<input type="number">
```

Accepts numeric values.

---

## Date

```html
<input type="date">
```

Displays a date picker.

---

## Radio Button

```html
<input type="radio" name="gender">
```

Allows selecting only one option.

---

## Checkbox

```html
<input type="checkbox">
```

Allows selecting multiple options.

---

## File Upload

```html
<input type="file">
```

Lets users upload files.

---

## Submit Button

```html
<input type="submit" value="Submit">
```

Submits the form.

---

## Reset Button

```html
<input type="reset" value="Reset">
```

Clears all entered values.

---

# `<textarea>`

Used for multi-line text.

Example:

```html
<textarea rows="4" cols="30"></textarea>
```

Used for:

* Address
* Feedback
* Comments

---

# `<select>`

Creates a drop-down list.

Example:

```html
<select>
    <option>MCA</option>
    <option>BCA</option>
    <option>B.Sc</option>
</select>
```

---

# `<option>`

Defines an item inside a drop-down.

Example:

```html
<option>Python</option>
```

---

# `<button>`

Creates a clickable button.

Example:

```html
<button>Register</button>
```

---

# Mini Project

**Student Registration Form**

Fields:

* Full Name
* Email
* Phone Number
* Password
* Date of Birth
* Gender
* Skills
* Course
* Address
* Resume Upload
* Submit Button
* Reset Button

---

# Interview Questions

1. What is the purpose of the `<form>` tag?
2. What is the difference between GET and POST?
3. Why do we use `<label>`?
4. What is the purpose of the `type` attribute in `<input>`?
5. Difference between radio buttons and checkboxes?
6. What is the purpose of `<textarea>`?
7. Why do we use `<select>` and `<option>`?
8. What is the purpose of the submit button?
9. What is the purpose of the reset button?
10. What is the difference between `<input>` and `<textarea>`?

---

# Key Points to Remember

* `<form>` creates a form.
* `<label>` describes an input field.
* `<input>` accepts user input.
* Radio buttons allow one selection.
* Checkboxes allow multiple selections.
* `<textarea>` accepts multiple lines of text.
* `<select>` creates a drop-down menu.
* `<option>` defines choices inside a drop-down.
* Submit sends the form.
* Reset clears the form.

---

# Day 4 Summary

✅ Learned HTML Forms

✅ Practiced different input types

✅ Understood GET and POST methods

✅ Created a Student Registration Form

✅ Ready to style forms using CSS in future projects
