# Website Performance Optimization portfolio project (ver.JD)

(guideline)
A README file is included detailing all steps required to successfully run the application and outlines the optimizations that the student made in index.html and views/js/main.js for pizza.html.

## How to run the application
Please go to this link below
https://storymessinger.github.io/frontend-nanodegree-mobile-portfolio/

To see the optimization result,
1. Use google pagespeed tool to inspect the speed of the page
2. use the chrome dev tools to inspect  the rendering speed :)

Enjoy!

## Optimizations currently done

### index.html (CRP optimization)
1. async-ed the google analyics
2. used image srcset for pizzeria.jpg for optimization
3. optimized the size of pizza.jpg
4. Inline-ed "style.css" of index.html 
5. ~~Compressed the  css and js file using gzip by grunt-compress~~
6. Found out its not gzip but 'minifing' that should be done. Minified.
7. 


### main.js (Getting rid of janks in rendering)
1. FSL problem solved with Pizza-Sliders
2. FSL problem solved related with moving pizza background
3. querySelector to getElementsByClassname


### Todo
- [ ] How to use javascript and var with css3 transform:translateX?
-  






### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
