
Source of Egram Website https://egram.tel

### Build

You must have [Gulp](https://gulpjs.com/) installed globally

- do `git clone`
- run `npm install`
- run `gulp`

### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory