* build 

```
$ npm install material-design-lite parcel-bundler node-sass
$ npm install -g parcel-bundler node-sass rimraf
$ sass -I node_modules src/scss/sphinx_mobigen_theme.scss sphinx_materialdesign_theme/static/sphinx_mobigen_theme.scss
$ ./node_modules/.bin/parcel build src/js/sphinx_mobigen_theme.js -d sphinx_mobigen_theme/static

$ sudo pip install sphinxtogithub

$ npm install 

$ npm run build
```

* docx 2 rst
```
$ pandoc -f docx index.docx  -t rst -o index.rst
$ unzip index.docx
$ mv ./word/media .
$ mogrify -format png media/*.*
```
