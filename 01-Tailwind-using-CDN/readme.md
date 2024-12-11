# 1. To use `Tailwind` using `CDN`(CDN = Link) We have to use this script `<script src="https://cdn.tailwindcss.com"></script>` in `<head>` tag of html file .

### index.html =>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tailwind easy way</title>
    <script src="https://cdn.tailwindcss.com"></script> <!-- Add this script to use Tailwind CSS directly in a simple HTML file -->
</head>
<body class="bg-slate-500">
    <h1 class="text-5xl bg-yellow-300 text-center font-black hover:bg-slate-900 hover:text-white py-5 ">
        Tailwind css works here
    </h1>
</body>
</html>
```

# 2. Install the `Tailwind CSS IntelliSense` Extension to get tailwind suggation code/class during coding.