## Website Performance Optimization portfolio project
-----------------------------------------------------


##How to test Pagespeed
-----------------------
1. Open the link https://developers.google.com/speed/pagespeed/insights/ in any browser.

2. Enter the url http://laxmi256.github.io. in edit box and click on Analyze button.

3. It then displays the Pagescore of the web application in both desktop and mobile.


##How to run this project
-------------------------

1. Clone the project from github link https://github.com/laxmi256/laxmi256.github.io.git to any local directory.

2. Open the project by opening the index.html file in any browser.


##How to test frame per sec
---------------------------

1. Open the project by opening the index.html file in google chrome.

2. Click the pizza link.

3. Open the dev tool by pressing Ctrl/Cmd + I and click on Timeline.

4. Start recording and then reload the application and scroll the page up and down.

5. Then stop recording and analyse the fps graph.


##How to check the time to resize pizza
---------------------------------------
1. Open the project by opening the index.html file in google chrome.

2. Click the pizza link.

3. Open the dev tool by pressing Ctrl/Cmd + I and click on Console.

4. By default the pizza slider is in the middle position showing the medium pizzas.

5. Move the pizza slider to left end and then towards the right end to generate small and larger pizzas.

6. The time to resize pizzas will now be displayed in the console.


##Steps taken for Optimizing index.html
---------------------------------------

1. Added media query for the render blocking print.css

2. Inlined the render blocking Google font css using web font loader.

3. Minified style.css, print.css and perfmatters.js.

4. Compressed profilepic.jpg image.

5. Added async tag to analytics.js and perfmatters.js


##Steps taken for Optimizing main.js
------------------------------------

1. Removed queries from for loops in changePizzaSize()

2. Changed updatePosition() functions

3. Compressed pizzeria.jpg image.

4. Minified style.css, bootstrap-grid.css and main.js.