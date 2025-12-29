### create a new repository on the command line
```echo "# tailwind-css4" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/rahuldogney02/tailwind-css4.git
git push -u origin main
```
### push an existing repository from the command line
``` git remote add origin https://github.com/rahuldogney02/tailwind-css4.git
git branch -M main
git push -u origin main
```
## install tailwind using command : 
- npm install tailwindcss @tailwindcss/cli
- src/in

put.css
- @import "tailwindcss"; 
- npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

```
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="./output.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
```

