#bootstrap-customize

Clone the repo.
```
git clone https://joaosousa1.github.com/bootstrap-customize
```

Change to folder bootstrap-customize.
```
cd bootstrap-customize
```

Install.

```
npm install
```

Edit files src/main.scss

Compile scss file and copy bootstrap.bundle.min.js file from node_modules to dist/js/bootstrap.bundle.min.js

```
npm run css-compile
```

Preview the result in preview.html

The compiled file go to /dist/css/main.css
Copy dist folder to your project and add your custom files to index.html 

```
<link rel="stylesheet" href="dist/css/main.css">
<script defer src="dist/js/bootstrap.bundle.min.js"></script>
```

