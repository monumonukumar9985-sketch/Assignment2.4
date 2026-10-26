# Assignment 2.4 — HTML Validation & Debugging

### 1. Buggy HTML Code (Before)

```html
<html>
<head>
<title>My Page
<body>
<h1>Welcome
<p>Hello <b>World</p>
<img src="photo.jpg">
</body>
</html>
```

### 2. Errors Identified

- Missing closing `title`, `h1`, and other tags.
- Incorrect nesting of `<b>` and `<p>`.
- Missing `alt` attribute in the image.
- Missing `DOCTYPE` and `lang` attributes.

### 3. Corrected HTML Code (After)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Page</title>
</head>
<body>
    <h1>Welcome</h1>
    <p>Hello <strong>World</strong></p>
    <img src="photo.jpg" alt="Sample photo">
</body>
</html>
```

### 4. Validation and Debugging

1. Open the page in Chrome.
2. Press **F12** and inspect the **Elements** panel.
3. Validate the HTML at https://validator.w3.org/

**Submission:** Submit before-and-after code and a screenshot of the corrected webpage.