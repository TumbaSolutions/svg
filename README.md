# svg
For our “Hello, Floormap!” example 

we will use a HTML page that consists of simple menu with 3 buttons when pressed sending events to the SVG to show specific rectangles representing a floor in the floormap. The HTML also has a info area to show what was clicked in the SVG and present that information in the HTML. When tapped on “Hall 7″ on 3rd floor in the SVG, the JS interface uses a callback to the HTML to change a “div” text content in the webpage. In this manner we can send events to the SVG and the SVG will change itself and when interacting with the SVG, it to send data to the HTML so the HTML can change itself. 

Check this article for more information "Interfacing with SVG"
[a link](http://tumba.solutions/blog/svg)