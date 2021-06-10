## What is a <div>?

In this step, we're going to look at how the ```<div>``` tag works and how it creates separate ****divisions** in a webpage. You will be able to change the information contained in the different divisions of the webpage and style them to look cool!

--- task ---

If working **online**, open the [starter project](https://trinket.io/html/780d3e38c5){:target="_blank"} in Trinket, or your preferred editor.
 
If working **offline**, open the project [starter file](http://rpf.io/p/en/webcomic-get){:target="_blank"} in your offline editor. If you need to download and install VS Code, you can find it [here](https://code.visualstudio.com/Download){:target="_blank"}.

You should see...
 
![starter project](images/starter_project.png)

--- /task ---

In the previous project, you learned that HTML provides the structure and content of a website using different 'tags'. In this project we are focusing on one specific type of HTML tag: ```<div>```.

The ```<div>``` tag is used to create a division or section in an HTML document. Think of ```<div>``` as creating a container into which you can put other HTML elements and style them together using CSS. Any sort of content can be put inside a ```<div>``` tag.

--- task ---
Have a look at the code in the first tab, ```index.html```. You'll see that the usual header information is included in the ```<head>``` tag. 

Inside the body of the website, you should first see the ```<h1>``` tag that contains the heading (feel free to change this to anything you like!), followed by a tag which says ```<div class=div1>```. 

This tag creates the division in your webpage, which we have assigned the class **div1**. The division ends at the ```</div>``` tag, and everything between these two tags can be styled using the ```style.css``` stylesheet.
--- /task ---

All of the ```<div>```s we create can be independently styled by creating rules for them in our stylesheet.  Let's have a look at some existing rules first, to see how they apply to our divisions.

--- task ---
Open the style.css file now. You should see the same sort of code in the stylesheet here as that in the last project, including declarations for tags like ```<p>```, ```<body>``` and all the heading tags. 

--- /task ---

You can name your divisions when you create them by adding the ```class=name``` into the tag. Whatever you set as the name for your division should be added to your stylesheet with a dot at the front like this:

```.name { }```

--- task ---
Scroll down to line 45 in style.css, to where the styling for the ```<div>``` tags begins. You will see some comments in the file, explaining that you can style each div in your index.html file using these declarations. Change the information included in the .div1 and .div2 rules now - you can use colour names from [here](https://www.w3schools.com/cssref/css_colors.asp) if you need some reminders!

Remember: You can switch back to ```index.html``` any time to see the changes you've made!
--- /task ---

We can also put ```<div>```s inside other ```<div>```s! Kind of like putting a box **inside** another box, and we can style both however we like! You can put **any** sort of content inside nested divisions. Let's have a look at how this works now.

--- task ---
Open the index.html file and scroll down to line 28. Under the comment, you should see a tag that opens a division classed **parent**. Inside this division there is a level 1 heading, some paragraph text and **another two divisions**. 
--- /task ---

The first division **nested** inside the parent division is called **child** and starts on line 32. You could call it anything you like - we are just using 'parent' and 'child' in this example. As you can see, it sits **inside** the parent division, but is styled quite differently.

The second nested division starts on line 42 and is also classed **child**. This means that while the content inside this division can be different, the **styling** will match the division above, and **any other division in your HTML where ```class=child```.** 

--- task ---
Change the formatting of the **parent** and **child** divisions now. 

Can you change the code in the HTML and the CSS so the two different **child** divisions are styled differently?

--- collapse ---
---
title: I need a hint!
---
**In the HTML:** Inside the second nested ```<div>``` tag (line 42), change the class to something else (like ```class=child2```).
**In the CSS:** Add a new declaration that starts with the name of your new class as it's selector (must be the same as the class used in the HTML - ```.child2``` in this example) and contains different formatting rules. (Or... copy-paste the existing ```.child``` declarations and change the selector and values!)

--- /collapse ---

--- /task ---

--- task ---
Edit the HTML and CSS files until they look awesome and you are ready to move on. 

Can you add a whole new ```<div>``` at the bottom of the page and style it uniquely?
--- /task ---

In the next step, we will make a 4-panel comic!

--- save ---