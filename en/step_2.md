## What is a <div>?

In this step, we're going to look at how the ```<div>``` tag works and how it creates separate ****divisions** in a webpage. You will be able to change the information contained in the different divisions of the webpage and style them to look cool!

--- task ---
If working **online**, open the [starter project](https://trinket.io/html/780d3e38c5){:target="_blank"} in Trinket, or your preferred editor.
 
If working **offline**, open the project [starter file](http://rpf.io/p/en/webcomic-get){:target="_blank"} in your offline editor. If you need to download and install VS Code, you can find it [here](https://code.visualstudio.com/Download){:target="_blank"}.

You should see...
 
![starter project](images/starter_project.png)

--- /task ---

In the previous project, you learned that HTML provides the structure and content of a website using different 'tags'. In this project we are focusing on one specific type of HTML tag: ```<div>```.

The ```<div>``` tag is used to group bits of HTML. Think of ```<div>``` as creating a box with other tags inside it. All the HTML in the ```<div>``` can have the same style.


You can name divisions when you create them by adding the ```class=name``` into the tag. Whatever you set as the name for your division should be added to your CSS stylesheet with a dot at the front like this:

```.name { }```

--- task ---
Look at the code in the first tab, ```index.html```. You'll see that the usual header information is included in the ```<head>``` tag. 

Inside the body of the website, **find** the tag which says ```<div class="title">```. 

This tag creates the division in your webpage, which we have assigned the class **title**. The division ends at the corresponding ```</div>``` tag on line 43, and everything between these two tags can be styled using the ```style.css``` stylesheet.

--- /task ---

We can also put ```<div>```s inside other ```<div>```s! Kind of like putting a box **inside** another box, and we can style both however we like! You can put **any** sort of content inside nested divisions. Let's have a look at how this works now.
<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Did you meet the <span style="color: #0faeb0">

The larger division created to hold others is called the <span style="color: #0faeb0">parent</span>. The first division <span style="color: #0faeb0">nested</span> inside the parent division is called <span style="color: #0faeb0">child</span> (and starts on line 21). You could call it anything you like - we are just using 'title' and 'panel' in this example. As you can see, it sits <span style="color: #0faeb0">inside</span> the parent division, but is styled quite differently.</p>

The second nested division starts on line 30 and is also classed **panel**. This means that while the content inside this division can be different, the **styling** will match the division above, and **any other division in your HTML where ```class=panel```.**

--- task ---
Find the other child ```<div>``` tags in your comic - there are four of them!

--- /task ---

All of the divs we create can be independently styled by creating rules for them in our CSS stylesheet.  Let's have a look at some existing rules first, to see how they apply to our divisions. 

--- task ---
Open the ```style.css``` file now. You should see the same sort of code in the stylesheet here as that in the last project. 

Find the CSS declarations for tags like ```<p>```, ```<body>``` and all the numbered heading tags you have seen before.

--- /task ---

--- task ---

Change the declaration on line 19 to another ```color``` - you can use colour names from [here](https://www.w3schools.com/cssref/css_colors.asp) if you need some reminders! This will style any text inside ```<h1>``` tags on your comic to be this colour.

--- /task ---

--- task ---
Scroll down to line 44 in style.css, to where the styling for the ```<div>``` tags called ```.title``` and ```.panel``` begins. These set out the styling rules for our divs assigned these classes. 

Change some of the values here, until you are happy with the way your comic looks. 

(Don't change ```float```, ```height``` or ```width``` as they will likely mess up your comic's layout!)

--- /task ---

--- task ---
Edit the HTML and CSS files until they look awesome and you are ready to move on. 

Can you add a whole new ```<div>``` at the bottom of the page and style it uniquely?
--- /task ---

In the next step, we will add the pictures for your comic panels!

--- save ---