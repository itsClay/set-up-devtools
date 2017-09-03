# set-up-devtools

Something for my fellow students and I to use while testing our js code in the chrome browser dev-tools.

paste code into your .aliases or .bashrc file
#### set-up-devtools myFilename


```
set-up-devtools() {
  echo "<!doctype html>
  <html>
  <head>
      <title>HTML Template example</title>
      <script type=\"text/javascript\" src=\"./$1\"></script>
  </head>
  <body>
  </body>
  </html>" > index.html
}

# chrome index.html
alias chrome="open -a 'Google Chrome'"
```

*EX: filename is*  **example.js**

commands:
1. `set-up-devtools example.js`

2. `chrome index.html` to open up the dev-tools
