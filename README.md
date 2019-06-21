Brittany Moyers
# Sprint-Challenge Applied Javascript - Lambda Times

## Instructions

## Self-Study Questions


1. What is the DOM?

DOM stands for 'document object model'. It's a language neutral API that forms a bridge between our code and the browser by creating an object oriented representation of the html.

2. What is an event?

Events are simply user interactions with the page. 

3. What is an event listener?

An event listener is an element with a callback function which watches for and responds to an event. 

4. Why would we convert a NodeList into an Array?

Converting NodeLists to Arrays is sometimes necessary in order to access the full functionality of arrays, such as '.map' and other methods not available to "array-like objects" such as a NodeList.

5. What is a component?

A component takes several pieces from across our code - HTML, CSS, and/or JavaScript, and puts them together into a reusable template that we have available whenever we need it. 

### Git Set up



## Minimum Viable Product

Your finished project must include all of the following requirements:

* [x] Look through the HTML code paying particular attention to the Tabs component and the Cards components. You will notice they share a data attribute. We will be using this data attribute to determine which cards should show when each tab is selected.

* [ ] Following the instructions in the `Tabs.js` file, complete the `TabLink`, and `TabCard` class components. It will look and feel very similar to the last project we worked on, but with a twist. Now, instead of one `Item` to display, we will need to display a collection of `Cards`. Think about ways to iterate over an array and manipulate each item.  **Note: You will need to un-comment the code after the lines of instructions.  The code is commented out so you can work error-free**

* [ ] Once you get your `Tab` component working properly add a couple more articles yourself and check out how it works.

## Stretch Problems

Your stretch challenge is to write the functionality of a `Carousel` component. You have the HTML and CSS already in place, simply un-comment the HTML in the `index.html` file. This is an advanced challenge, so you are not expected to be able to complete it. If you begin and don't finish, you should still submit with what you have. You may reference the `Tabs.js` file for assistance.

* [ ] Complete the carousel functionality in `Carousel.js`

* [ ] If you complete the Carousel, add functionality so that the carousel slides when the buttons are pressed instead of just appearing.

* [ ] Create an 'infinite loop' carousel. In which as long as you click on an arrow, the array of images will loop over itself.

* [ ] If you have finished the above, play around with the styling on all the components, and understand how each is built.
