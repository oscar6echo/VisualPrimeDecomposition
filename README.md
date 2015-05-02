## Visual Prime Decomposition##

Inspired by blog posts [here](http://mathlesstraveled.com/2012/10/05/factorization-diagrams/) and [there](http://chrisrzhou.datanaut.io/blog/tutorials/2015/02/22/dances-with-factors-tutorial/), I wanted to write such animation entirely in a [Jupyter] notebook.

In the process I made slight adjustments:  
+ I changed the disposition of the circles so that they fill as much space as possible, using a bit of trigonometry, so that (1) circles remain visible even for large numbers, (2) there is never overlapping.
+ I added a zoom in/out feature to capture the fractal aspect of such diagrams.
+ The input field accepts expression like '2*5*7*13' so that you can get the pattern without a side calculator.


The notebook makes heavy use of the `%%javascript` magic and the impressive [d3.js](d3js.org) library.
The function `write_js_to_output` is necessary to store the js code in an output cell, which enables (1) the notebook to run the js stored in the outpout cells upon load without the user having to manually run the cells, (2) nbconvert to create a standalone html page containing the notebook output ready for posting. [Here] is the result.

