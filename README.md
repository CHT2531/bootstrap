# Introduction to Bootstrap

* Download index.html. 
  * Open it in a text editor and in a browser
  * Note the link to the Bootstrap CSS file
  * Note the page already has some default styling.

## Using Bootstrap classes
* Style the page simply by using Bootstrap classes i.e. don't write any of your own CSS.
* Try and make the page look like the following image
 ![Example page](tbl.png "Example")
* Start by focussing on the following CSS properties. Most of these are covered by the utility classes in Bootstrap https://getbootstrap.com/docs/5.0/utilities
  * Padding 
  * Margins
  * Borders
  * Font weight
  * Line height
  * Colours. You won't be able to match the colours exactly. Choose colours from Bootstrap that are as close as you can get. 

## Overriding the Bootstrap defaults
* To get the right font for the headings (Garamond), the right colours for the headings (#45b2f5) and background (#d6d5d5) create your own CSS file that will overwrite the Bootstrap CSS.

## Controlling layout
* Have a look at the layouts and grids (https://getbootstrap.com/docs/5.0/layout/grid/) and see if you can create a simple responsive design where the layout is single column on small displays and switches to two columns on larger displays e.g.
![Responsive xample page](tbl-responsive.png "Responsive Example")
* The design should be fixed width and always sit in the center of the page.
  
## Customising Bootstrap
The problem with the above is that: 
1. We are over-writing the exsiting CSS with our own CSS
2. We are asking the user to download the entire Bootstrap framework when we are only using a limited number of features. 

Ideally we should import and extend the Bootstrap Sass code to create our own streamlined custom version of Bootstrap. Bootstrap provide info on how to do this at https://getbootstrap.com/docs/5.0/customize/sass/. They also provide a started project at https://github.com/twbs/bootstrap-npm-starter.
 
## There's lots more
* There's lots more you can do with Bootstrap e.g. components. Components are reusable commonly used UI elements e.g. navigation bars, accordians, buttons. Bootstrap 'off the shelf' components written in HTML, JavaScript and CSS which we can then customise. 
