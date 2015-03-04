The project includes the following goals
1.	Achieve PageSpeed score of 90 or above on Cameron’s portfolio page
2.	Achieve a framerate of 60 fps for pizza.html
3.	Time to resize pizza size using scrollbar on pizza.html page is less than 5 ms

Goal #1 changes
1.	Moved css styles inline into index.html
2.	Loading analytics async not to halt loading
3.	Using optimized images
Goal #2 & 3
1.	Refactored updatePosition and changePizza functions
2.	Used CSS transform with translateX
3.	Reduced nbr of pizzas
4.	Added  the following for the mover class in style.css
 -webkit-backface-visibility: hidden;
  -webkit-transform: translate3d(0, 0, 0);
  -webkit-perspective: 1000;
5.	Using minified main.js 
6.	Using compressed images

In order to test the portfolio page, please open up index.html file in Chrome. In order to test pizza page, the pizza.html page under views folder needs to be opened in Chrome.  Please note that all the files included in the repository must be downloaded for pages to run correctly.
