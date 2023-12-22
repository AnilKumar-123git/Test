# Test
Game design concept

# Interactive Tutorial

Welcome to the interactive tutorial! Let's get started.

## Step 1: Introduction

Blah blah blah...

## Step 2: Coding Section

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Tutorial</title>
</head>
<body>

<h2>Write your HTML, CSS, and JavaScript code here</h2>

<!-- Add the CodeMirror textarea -->
<textarea id="code" name="code">
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Tutorial</title>
</head>
<body>

<h1>Hello, World!</h1>

</body>
</html>
</textarea>

<!-- Add the CodeMirror script -->
<script src="https://codemirror.net/lib/codemirror.js"></script>
<script src="https://codemirror.net/mode/htmlmixed/htmlmixed.js"></script>

<script>
    // Initialize CodeMirror
    var editor = CodeMirror.fromTextArea(document.getElementById("code"), {
        lineNumbers: true,
        mode: "htmlmixed"
    });
</script>

</body>
</html>
