# Healthy Recipes

Using CSS selectors, you’ll give a recipe website some new style!

1. Before you begin, take a look at the site’s structure in **index.html**.
<br /><br />Start by making the image at the top of the page a little smaller. Navigate to **style.css** and write a CSS selector for the ```img``` tag.
<br /><br />Within its curly braces, write:
<br /><br />```height: 150px;```
<br /><br />Try experimenting with the 150 number and observing the results.

2. The font size of the recipe description should be larger. In **style.css**, write a CSS selector for the ```.description``` class.
<br /><br />Within its curly braces, add the following CSS:
<br /><br />```font-size: 20px;```

3. Next, let’s style the cooking time. The element on line 15 of **index.html** has an ```id``` attribute of cook-time. Navigate to **style.css** and add a ```cook-time``` ID selector.
<br /><br />Inside of its curly braces, write:
<br /><br />```font-weight: bold;```

4. Now, let’s change the bullet points of the ingredient list to squares instead of circles. Start by writing a selector for the ```li``` elements inside of the ```.ingredients``` element.
<br /><br />Then, write this inside of its curly braces:
<br /><br />```list-style: square;```

5. Next let’s make the time for each preparation step appear gray. In **style.css**, write a selector for ```p``` elements that also have a class of ```.time```.
<br /><br />Then, inside of this selector’s curly braces, write:
<br /><br />```color: gray;```

6. At the bottom of the page, there’s a link to the full recipe. Let’s make the link a different color.
<br /><br />Notice that in **index.html**, on line 42, there is a ```p``` element with a class of ```citation```, then an ```a``` element inside of it with a class of ```external-link```. Navigate to **style.css** and write a selector using ```external-link``` class.
<br /><br />Then, add this code inside of the selector’s curly braces:
<br /><br />color: ```SeaGreen;```

7. Finally, let’s make the font Helvetica instead of the default Times New Roman. Instead of writing multiple selectors to apply the ```font-family``` property, write a selector that applies a font-family attribute to all text at once.
<br /><br />The selector should target the ```h1, h2, p, and li``` elements.
<br /><br />To change their font, include this line of code inside the curly braces:
<br /><br />```font-family: Helvetica;```
