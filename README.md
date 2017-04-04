## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To view the final project please view [this link](http://kjwhitla.github.io/frontend-nanodegree-mobile-portfolio/)

### Changes to the pages

#### index.html
To improve performance:
- Optimized all images across the web pages
- Added the async attribute across javascript files
- Minify javascript and css files
- Removed render blocking JS
- Deferred render blocking CSS loading 

#### views/js/main.js
- Reduced the time interval of the pizza position update
- Corrected display of pizza slider
- Improved size and width change
