# module5Solution

Coursera course: HTML, CSS, and Javascript for Web Developers

Last assignment and you are DONE!

Time to complete: About 30 minutes.

Ask questions in Discussions if you get stuck! We are all learning, and going through getting stuck and then unstuck (even with someone's help) can be a very valuable learning experience!

Summary: In this assignment, we are going to have a bit of fun with our built restaurant web application. The front page of our web app contains 3 clickable tiles: Menu, Specials, and Map. If you click on the Specials tile, you will be taken to a single category page where all the menu items that belong to the Specials menu category will be shown. Your task in this assignment is to alter this behavior such that when the user clicks on the Specials tile, the web app takes the user to a random single category menu page, listing menu items in the category, be it "Lunch", "Dinner", "Sushi", etc. That way, any random category can become the Specials! What fun! (not! :-) )

In order to accomplish this, we need to change the home HTML snippet and, besides pulling it dynamically from the server, also insert a random category short_name into the function call of the following code. Previously, the code to send the user to the "Specials" category was this:

<a href="#" onclick="$dc.loadMenuItems('SP');">
For this assignment, we changed this line to prepare it for a random category short_name to be this:

<a href="#" onclick="$dc.loadMenuItems({{randomCategoryShortName}});">
Here is what you will need to complete the assignment:

(If you haven't already) Create a GitHub.com account and a repository that you will use for this class.

(If you haven't already) Follow the Development Setup Video (beginning of Module 1) instructions on how to create a repository and set it up such that you can host and view your finished web pages on GitHub Pages, i.e., GitHub.io domain name. You will need to provide that URL for your peer review.

Create a folder in your repository that will serve as a container folder for your solution to this assignment. You can call it whatever you want. For example, module5-solution or mod5_solution, etc.

You will need to download the starter files for this project and copy them into your solution container folder (e.g., into 'module5-solution'). Since assignments and starter code get updated from time to time, don't assume that you have the latest version already on your system. The best way to ensure that you are working with the very latest starter code is either 'git clone' the fullstack-course4 repository into a new directory OR, if you've already done 'git clone' previously, you can simply open up your command prompt (cmd on Windows or Terminal on Mac), navigate to the folder where the fullstack-course4 repository was previously cloned into and do: git pull
