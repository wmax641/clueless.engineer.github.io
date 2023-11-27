# clueless.engineer.github.io
clueless.engineer website

## DevOps and deploy notes
* Install uglify CSS. By default installs to `./node_modules/uglifycss/uglifycss`
```
npm install uglifycss
```

* Develop and make changes to `index-dev.html`

* Use uglifycss (remember it's installed locally to `/node_modules/uglifycss`) 
```
node_modules/uglifycss/uglifycss  index-dev.html  > index.html
```
