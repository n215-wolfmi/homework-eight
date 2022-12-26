# Homework Eight

Author: Matthew Wolf, IUPUI, Spring 2022

Web 4 Link to homework assignment:
https://in-info-web4.informatics.iupui.edu/~wolfmi/n215/homework-eight/ 

This homework assignment is solely focused on creating a dynamic one-page website where, using javascript along with jQuery, different pages of content can be slotted into a specific div on the page. This assignment is a good view of how jQuery can be used to make dynamic websites.

## The app.js process

In this case, the app.js file, on page load, activates a few functions that check the a tags in the nav for clicks, grab the id from the clicked a tag, pass that id into another function that combines the id with the word "Content". 

This combined string is now forms a variable that already exists within the app.js file whyich stores the page contents for a specific page. 

This HTML content from the variable is then loaded into a div with the id of #app on the page. 

On load and a reload of the page, the content will show the index page.
