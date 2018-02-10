# interactive-storybook

Create an interactive web comic with your knowledge of HTML and CSS!

![Final Page Example](https://github.com/junior-devleague/interactive-storybook/blob/master/assets/example.png)

## Objective

Use **HTML Elements**, **CSS Styles** and **CSS Animations** to create a storybook that the user can interact with!

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of CSS Keyframes.
* Basic understanding of Flexbox.

## Concepts

HTML | Description
-----|------------
HTML | **H** yper **T** ext **M** arkup **L** anguage used to create the structure of web pages.
element | An element is an individual part, or a building block, of a web page.
attribute | A modifier of an element.
div | A container element.
p | A paragraph element.

CSS | Description
----|------------
CSS | **C** ascading **S** tyle **S** heets that describes how HTML elements are displayed.
flexbox | A layout mode to improve how items are aligned or ordered on a page even within items of unknown size.
position | A property that specifies the type of positioning method used (static, relative, absolute, or fixed). Play around with the different types here: https://www.w3schools.com/cssref/playit.asp?filename=playcss_position&preval=absolute.

Note: Flexbox comes in very handy! It is helpful to remember the following common CSS Flexbox properties.
* ```display: flex;``` Use this to activate Flexbox! If you do not have this property, other flexbox properties will not work.
* ```justify-content: center | space-around | space-between;``` Control horizontal spacing.
* ```align-items: center | space-around | space-between;``` Control vertical spacing.
* ```flex-direction: column | row;``` Control the direction of items.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:

1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS file
* assets folder (from this folder)
3. Link all of your files correctly.

### Part II HTML

To complete Part II, fulfill the following requirements:

1. Create a ```div``` with an ```id``` of "container". **Inside of this div**, create the following:

* ```div``` with a ```class``` of "area"
  * ```div``` with a ```class``` of "innerarea"
    * ```img``` with the ```src``` to the "panel1.png" file.
    * ```img``` with the ```src``` to the "panel2.png" file.

This part should appear like this in your HTML file:

``` HTML
<div class="area">
  <div class="innerarea">
    <img src="assets/panel1.png" alt="">
    <img src="assets/panel2.png" alt="">
  </div>
</div>
```

**See how things are nested with indentation? Indentation is important to show what elements belong to what.**

We will continue to create similar patterns.

**Inside of the div with id of container, continue to create the following:**

* ```div``` with a ```class``` of "area"
  * ```div``` with a ```class``` of "innerarea"
    * ```img``` with the ```src``` to the "panel3.png" file.
    * ```img``` with the ```src``` to the "panel4.png" file.

---

* ```div``` with a ```class``` of "area"
  * ```div``` with a ```class``` of "innerarea"
    * ```img``` with the ```src``` to the "panel5.png" file.
    * ```img``` with the ```src``` to the "panel6.png" file.
    * ```img``` with the ```src``` to the "panel7.png" file.

---

* ```div``` with a ```class``` of "area"
  * ```div``` with ```id``` of "final" and a ```class``` of "innerarea"
    * ```img``` with the ```src``` to the "panel8.png" file.

---

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue1"**. You don't have to put anything in there yet.

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue2"**. You don't have to put anything in there yet.

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue3"**. You don't have to put anything in there yet.

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue4"**. You don't have to put anything in there yet.

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue5"**. You don't have to put anything in there yet.

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue6"**. You don't have to put anything in there yet.

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue7"**. You don't have to put anything in there yet.

* ```p``` with ```class``` of "speech" and ```id``` of **"dialogue8"**. You don't have to put anything in there yet.

---

Great job!

### Part III CSS

To complete Part II, fulfill the following requirements:

1. Target the ```body``` element.
* Set the ```margin``` to 0px. This will get rid of any white spaces on the edges of the body.

2. Target the ```id``` of "container".
* Set the width to the **full** view width of the window.
* Set the height to "auto", meaning it will take up whatever height to make sure it fully wraps around all of the elements inside of it.

3. Target the ```class``` of "area".
* Set the width to be **as wide as its parent element**.
* Set the height to be 400px.
* Give it a top margin of 10px. *What is the property that controls that?*
* Activate flexbox!
* Arrange the elements in a ROW using flexbox.
* Give horizontal SPACE-AROUND the elements using flexbox.
* CENTER the items vertically using flexbox.

4. Target the ```class``` of "innerarea".
* Set the height to 280px.
* Set the width to 80% of its parent element.
* Activate flexbox!
* Arrange the elements in a ROW using flexbox.
* Put horizontal SPACE-BETWEEN the elements using flexbox.

5. Target the ```class``` of "panel".
* Set the height to be **as tall as its parent element**.

6. Target the ```id``` of "final".
* Activate flexbox!
* CENTER the items horizontally using flexbox.

7. Target the ```class``` of "speech".
* Set the background color to white.
* Make the edges a little curvy using the ```border-radius``` property.
* Set the position to absolute. This makes it so that we can adjust the location of the elements using pixels for left, top, bottom, and right properties. It will also always stay there.
* Activate flexbox!
* CENTER the items HORIZONTALLY AND VERTICALLY using flexbox.
* Set the box-shadow to ```0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22)```. This gives us a nice shadow for our dialogue bubbles.
* Set the text-align property to "center" which will center our text.

**For dialogue1 through dialogue 8, adjust the following:**
* size
* location on the page
* text  

Make a story out of the panels! Each image should have 1 dialogue bubble near or next to it like the example at the top of the page.

8. Create a ```CSS Animation``` that adds a border to the dialogue bubbles when you HOVER on the dialogue bubbles. *Hint: Pseudoselectors: https://www.w3schools.com/cssref/sel_hover.asp, CSS Animation: https://www.w3schools.com/css/css3_animations.asp*

## Stretch Goals
1. Create an audio element of an animal sound in your HTML and an onclick attribute on the body element. Create a JavaScript file. Make it so that we the sound plays when we click anywhere on the webpage!

2. Create an even more interactive story by adding buttons to change the dialogue and image on click!
* Create a javascript file.
* Create 2 buttons in your HTML file.
* In your JS file, create a variable to store each button by its ID.

Example:
``` JavaScript
var button1 = document.getElementById('idforyourbutton!')

```

* Create a variable to store the dialogue container that you have by its ID. This will allow us to change it later when we click on a button.

* Create a variable to store the image by its ID.

* Create an onclick function! There are many ways to handle clicks. In this case, we will use the onclick function as follows:

``` javascript
button1.onclick = function() {
  // Change the innerHTML of your dialogue!
  // Change the source of your image!
}
```
* When you click on the button, the code inside of your onclick function will run. When we click on the button, we want to 1). Change the dialogue, and 2). Change the image!
  * 1). Change the dialogue.
    * Set the inner HTML of the dialogue container to the new dialogue like in this example.
    ``` javascript
    dialogue.innerHTML = "New dialogue!"
    ```
  * 2). Change the image.
    * Set the src property of the image to the new image source like in this example.
    ``` JavaScript
    image.src = "assets/newimage.png";
    ```
