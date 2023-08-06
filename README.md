# module5Solution

Coursera course: HTML, CSS, and Javascript for Web Developers

Last assignment and you are DONE!

Time to complete: About 30 minutes.

Ask questions in Discussions if you get stuck! We are all learning, and going through getting stuck and then unstuck (even with someone's help) can be a very valuable learning experience!

Summary: In this assignment, we are going to have a bit of fun with our built restaurant web application. The front page of our web app contains 3 clickable tiles: Menu, Specials, and Map. If you click on the Specials tile, you will be taken to a single category page where all the menu items that belong to the Specials menu category will be shown. Your task in this assignment is to alter this behavior such that when the user clicks on the Specials tile, the web app takes the user to a random single category menu page, listing menu items in the category, be it "Lunch", "Dinner", "Sushi", etc. That way, any random category can become the Specials! What fun! (not! :-) )

In order to accomplish this, we need to change the home HTML snippet and, besides pulling it dynamically from the server, also insert a random category short_name into the function call of the following code. Previously, the code to send the user to the "Specials" category was this:

<a href="#" onclick="$dc.loadMenuItems('SP');">
For this assignment, we changed this line to prepare it for a random category short_name to be this:
