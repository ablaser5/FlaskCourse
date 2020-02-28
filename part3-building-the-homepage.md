# Flask Web Development Course

#### Part 3: Building the Homepage
```text
In this section, we will be focusing on building the home page of the application.
We will concentrate on the front-end to familiarize you with concepts used to build out the 
rest of the application.
```

1. Add an "index.html" file to the templates directory
1. Add an "style.css" file to the static directory
1. Add an "index.js" file to the static directory
1. Copy the code snippet in the "index.html" file:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Home | Online Store</title>
	<link rel="stylesheet" type="text/css" href=" {{ url_for('static', filename='style.css') }} ">
	<script type="text/javascript" src=" {{ url_for('static', filename='index.js') }} "></script>
</head>
<body>
	<h2>Your Website is Successfully Configured</h2>
</body>
</html>
```
1. Copy the code snippet in the "style.css" file:
```css
html {
	font-family: sans-serif;
	text-align: center;
}
```