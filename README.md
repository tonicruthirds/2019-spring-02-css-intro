# CoderBabez

##  Week Two - Intro to CSS

### Objectives
Create your first CSS file, link it to your HTML page. Learn about selectors, properties and values in CSS.

### Vocab
* CSS
* Linking
* Properties and Values
* Tag / ID / Class Selectors

### Introduction
CSS can be an extremely powerful tool! Check out [CSS Zen Garden](http://www.csszengarden.com/) to get inspired. All of these pages use exactly the same HTML file - the only change is the CSS.

### Lesson - Intro to CSS:
Last week we learned that HTML provides the data and the structure for our websites.
This week we're learning about CSS, which provides the visual style and layout for our website.

1. Let's create our first css page. Add a file to your project called main.css (note the file extension)

2. Our CSS won't do anything to our HTML page unless we link them together. Link to your new CSS file by adding the following tag to the `<head>` of your HTML file.

```html
<link rel="stylesheet" type="text/css" href="main.css">
```

4. Time to add our first style! In your CSS file, add the following code:

```css
body {
	background-color: #DBECFC;
	color: #333;
}
```
There are three important parts of this rule: the selector (body), the property (background-color), and the value (#DBECFC).

5. Selectors: Selectors tell us what elements on the page we want to apply our CSS rules to. There are three main types of selectors
⋅⋅* Tags: selects every instance of that tag in your HTML
```html
	<p>I'm a paragraph!</p>
```
```css
	p{
		color: blue; /* I make the paragraph text blue */
	}
```
⋅⋅* Classes: selects every element with that class attribute
```html
	<p class="subheaders">I'm a paragraph!</p>
```
```css
	.subheaders{
		color: blue; /* I make only the text in the elements with the subheader class blue */
	}
```
⋅⋅* IDs: selects every element with that id attribute
```html
	<p id="byline">I'm a paragraph!</p>
```
```css
	#byline{
		color: blue; /* I make only the text in the element with the byline id blue */
	}
```
6. Tag selectors are great for general, base styles - like changing all the font to arial, or the back ground of the page to blue. IDs should only be applied to important unique objects like your header or your nav. IDs should only be used on one element, and not repeated. Classes are great when you have a group of elements that you want to be styled the same way - like turning some of the paragraphs blue, but not all of them.

7. CSS Property / Value pairs describe how you want to style the element that you have selected. You can put several properties within one selector, as long as they're all inside the curly brackets {}. Try the following properties: `font-family`, `background-color`, `color`, `border`


### Practice
Open up the recipe-page homework and follow the instructions!

### Final Thoughts
Today we learned how we can use CSS to add style to our pages.
Next week we’ll take a look at how CSS can change the layout of our pages by creating space, columns, and centering elements.
