# My Class 5 Reading Notes

## CSS (Cascading Style Sheets):
CSS allows you to create great-looking web pages and add design. It is a language for specifying how document are presented on the webpage.

We have 3 different types of stylesheet:
### * External

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

* Internal:

<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

* Inline

<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>

## CSS syntax
It is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.
For example: 
h1 {
    color: red;
    font-size: 5em;
}


Here is the link to my website: https://github.com/timothee2022