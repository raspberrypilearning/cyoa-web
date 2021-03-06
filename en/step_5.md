## Style up your story with CSS

In this step, we're going to use the CSS stylesheet you created to make your story website really pop! 

--- task ---
Open your **style.css** file now, and you will see that it is blank. 

Add the rules for the different tags you have created into the sheet, remembering to add the curly brackets like this, so you can add the declarations inside them:

```body { }```
```a { }```
```h1 { }```
```p { }```

--- collapse ---
---
title: Tags reminder
---

You should create rules for all the tags you used to create your story pages. In case you forgot what they are, here's a quick list:

+ ```body```: the main part of your page
+ ```p```: the text or paragraphs that make up your page
+ ```h1-h6```: the different sized headings
+ ```ul``` & ```ol```: unordered and ordered lists
+ ```span```: special text you want to highlight
+ ```img```: images on your page
+ ```div```: creates segments of your page you can style differently
+ ```a```: hyperlinks

--- /collapse ---

--- /task ---

Now that you have set up rules for all the tags you've used in your website, you should start adding the declarations that will create your styling. 

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;"> CSS Stylesheets were designed to be **portable** - you can use one stylesheet across multiple websites easily to style them all the same way. If you've previously created a stylesheet you really love, you can use it here and it will work!</p>

--- task ---

Go back over your [previous projects](https://learning-admin.raspberrypi.org/en/projects/edit-the-web/2) to remind yourself of some of the declarations used in CSS rules. 

For example, the CSS rules for your paragraph text might look like this to have it on the left side of your page and coloured ```AliceBlue```:
```css
p {
  font-family: arial;
  text-align: left;
  color: AliceBlue;
}
```

--- collapse ---
---
title: CSS Colours
---
You can find a full list of CSS colours [here](https://www.w3schools.com/cssref/css_colors.asp) to help make it funky!

Remember: you can use both the names of the colours and the Hex codes to define them!
--- /collapse ---

--- /task ---

--- save ---