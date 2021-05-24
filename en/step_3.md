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

--- task ---
Put the ```<a>``` tag before and the ```</a> tag after the words you would like to hyperlink, like this:

```<a>these are the words I want to link</a>```

--- /task ---

You should see the words change colour in your website once you add the tags, but it won't turn your pointer into a hand yet. This is because we haven't yet added the ```href```. Href stands for **hypertext reference**, or the URL where you want to send your reader. Without it, our hyperlink will go nowhere! 

--- task ---
Inside the ```<a>``` tag at the start of your new hyperlink add the following declaration and the name of the page you want the hyperlink to go to, like this:

```<a href=treasure.html>these are the words I want to link to</a>```

In this example, I am linking to the HTML file I have created called treasure.html - you should add the name of **your own website** here instead.

--- /task ---

You should now see the mouse pointer become a hand, as there is now a **target URL** in my hyperlink.


--- save ---