## Link your pages with hyperlinks

In this step, we're going to take all of your webpages and link to them through the choices you offered your reader. Before we do that though, we need to understand a little bit more about hyperlinks and how they work.

You've definitely seen hyperlinks before (you followed one to get to *this* web page!) Links are found on nearly all web pages. They allow users to navigate their way through the internet from page to page, just by clicking. You know they are there because when you move your mouse pointer over a hyperlink it becomes a little hand.

By default, links will appear as follows in all browsers (but you can change this with CSS!):

+ An **unvisited** link is underlined and **blue**.
+ A **visited** link is underlined and **purple**.
+ An **active** link is underlined and **red**.

--- task ---
Open your introductory page for your story. This is the first page your reader will see when they begin. 

Look through your text and find the words you would like to turn into a hyperlink to another page. (This will probably be an important word or phrase in your text.)
--- /task ---

The ```<a>``` tag is the one used by developers to create hyperlinks.

There are two kinds of hyperlink you can use when developing websites; **relative** and **absolute** hyperlinks:

+ **Absolute** hyperlinks are the full URL (web address) of the website, which includes the ```http://www.``` part. These can be used to link to any website on the internet.

+ **Relative** hyperlinks (the ones we are using today) are considered **local** links, in that they can only lead users to websites on the same **domain**. (That's the bit after the www!) This is great for developers who want to make sites that can be easily moved, as you only need to change the domain one time and *all* the pages will automatically redirect their links to the right place. 

--- task ---
Put the ```<a>``` tag before and the ```</a> tag after the words you would like to hyperlink, like this:

```<a>these are the words I want to link</a>```

--- /task ---

You should see the words change colour in your website once you add the tags, but it won't turn your pointer into a hand yet. This is because we haven't yet added the ```href```. Href stands for **hypertext reference**, or the URL where you want to send your reader. Without it, our hyperlink will go nowhere! 

--- task ---
Inside the ```<a>``` tag at the start of your new hyperlink add the following declaration and the name of the page you want the hyperlink to go to, like this:

```<a href="treasure.html">these are the words I want to link to</a>```

In this example, I am linking to the HTML file I have created called treasure.html - you should add the name of **your own website** here instead.

--- /task ---

You should now see the mouse pointer become a hand, as there is now a **target URL** in your hyperlink! 

--- task ---
CLick the new hyperlink to make sure it leads to the right page! 

If it doesn't work, check your spelling for the HTML filename you are aiming for!
--- /task ---

--- task ---
Add the ```<a href="">``` and ```</a>``` tags to all the different pages in your , making sure the links point to the correct files. Click the links to test them.

--- collapse ---
--- 
title: Pro Tip!
---
You can add a ```target``` to your tag, which will open links in a new window or tab!

Simply add ```target="_blank"``` to after your href like this:

```<a href="treasure.html" target="_blank">```

--- /collapse ---

--- /task ---

You can also make any images you have on your page into hyperlinks by putting the ```<a>``` tags **outside** the ```<img>``` tags like this:

```<a href="treasure.html"> <img src="treasure.jpg" alt="The treasure chest!"> </a> ```

Once you have all your links added, the next step is to style your story with CSS!

--- save ---