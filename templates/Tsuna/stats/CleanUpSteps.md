Remove `<link>` at the start of code

Minify entirety of `my-header` class

Remove leading spaces from rest of document (search for `^ ` in Notepad++ or similar)

`fs.writeFileSync('test.html', fs.readFileSync('./dist/main.html', 'utf8').replace(/\n */g, '\n'))`

Minify CSS file and add to style tags