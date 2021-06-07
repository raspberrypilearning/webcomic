## What is a <div>?

In this step, we're going to look at how the ```<div>``` tag works and what it does in a webpage. You will be able to change the information contained in the different divisions of the webpage.

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

Inside the body of the website, you should first see the ```<h1>``` tag that contains the heading (feel free to change this to anything you like!), followed by a tag which says ```<div class=div1>```. This tag creates the division in your webpage, which we have given the class **div1**. The division ends at the ```</div>``` tag, and everything between these two tags can be styled using the ```style.css``` stylesheet.
--- /task ---

--- task ---
Open the style.css file now. You should see the same sort of code in the stylesheet here as that in the last project, including declarations for tags like ```<p>```, ```<body>``` and all the heading tags. 

--- /task ---

--- task ---
Scroll down to line 45 in style.css, to where the styling for the ```<div>``` tags begins. You will see some comments in the file, explaining that you can style each div in your index.html file using these declarations. Change the information included in the .div1 and .div2 rules now - you can use colour names from [here](https://www.w3schools.com/cssref/css_colors.asp) if you need some reminders!

You can switch back to ```index.html``` any time to see the changes you've made!
--- /task ---

--- save ---