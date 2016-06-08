### Introduction to New Material ("I Do")
#### Handlers

An **event handler** is a piece of code that runs after an event has occured. Example of events include a key press on a keyboard and the scroll on a mouse. 

#### `Click` Handler

A common kind of **handler** is a **`click` handler** which runs after the mouse has been clicked over a certain element. Let's suppose we had HTML code like so:

```
<html>
  <head>...</head>
  <body>
    <button class="btn">Click me!</button>
  </body>
</html>
```
Clicking on the button will not do anything. Let's add a **click handler** to change that:

```
$(".btn").click(function()
{
  alert("Yay! You clicked me.");
});
```

Clicking on the button will now trigger a pop-up window (or alert) with the following text: "Yay! You clicked me."

### Guided Practice ("We Do")

Now we're going to practice jQuery **handlers** together. Let's open the Cloud9 workspace "jQurey-practice" together.

Using a **`click` handler**, make the image on the page change to a different image when clicked.


### Independent Practice ("You do")

Create a new page in your workspace called `day2.html`.

1. Using HTML, place a button, an image, and some text on your site.
2. Place a **click handler** on the button that displays an alert box when clicked. 
3. Use a **`mouseover` handler** to change the image when someone hovers their mouse over the image.  

**Bonus:** Use a **`scroll` handler** to change the text when someone scrolls over the image.

**Note:** Tags from the index page may need to be changed or added in order to not affect the layout og day2.html
	


### Closing

Today, you learned about jQuery. This is important because jQuery enables us to dynamically interact with our HTML and CSS. Next, we will learn about interacting with jQuery project.