# NickZack-Theme
NickZack wordpress development theme, as bare bones as it can be, includes GULP and auto JS deployment based on page url. work in progress.


cd into 'nickzack' main directory
npm install gulp-sass

gulp watchAll to enable browsersync and make live site sass changed that compile to /build/css/compiled/main.css

gulp min  to minifiy /build/css/compiled/main.css and put it in /build/css/compiled/minified/main.css - for production 
