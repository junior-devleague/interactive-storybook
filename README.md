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
  * ```div``` with a ```class``` of "innerarea"
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
