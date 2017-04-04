## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To view the final project please view [this link](http://madebykeegan.com/frontend-nanodegree-mobile-portfolio/)

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

### How to Run
To run the website follow these methods
- download the repository, and directly open index.html with a browser
- create a HTTP server on the root folder using Python, apache or other similar web server. Steps below. 

1. Using the command prompt or terminal

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 9292
  ```
2. Open a browser and visit localhost:9292 (http://localhost:[your_port])
