# Gulp
---

- Install

```bash
npm install --save-dev gulp
```

- Create a gulpfile.js

````javascript
var gulp = require('gulp');

gulp.task('default', function () {
   gulp.src('./node_modules/materialize-css/dist/css/materialize.min.css')
      .pipe(gulp.dest('./assets/css'));
});

gulp.task('default', function () {
   gulp.src('./node_modules/materialize-css/dist/js/materialize.min.js')
      .pipe(gulp.dest('./assets/js'));
});
````

- Run gulp

```bash
gulp
```
