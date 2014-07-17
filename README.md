mendix-framework-styling
========================

This is the default SCSS framework the Mendix UX team created. 

## Features

 * Uses Bootstrap framework
 * Uses SCSS partials to help structure the CSS
 * Uses Compass to take advantage of CSS3 mixins (no prefixes needed)

## How To Use

Mendix Framework uses SASS and Compass, which rely on Ruby. However you can install [Scout](http://mhs.github.io/scout-app/) to run Sass and Compass in a self-contained Ruby environment, letting you effortlessly manage all of your Sass projects with a handful of clicks. 

#### Setup Scout

Add your Mendix project in Scout and select the styles\lib folder as the input and output folder for the stylesheet directory. Press play!

#### Edit the SCSS files

When you make changes to any of the scss files, your lib.css file will be automatically updated. You don't edit lib.css directly, compass takes care of that for you.