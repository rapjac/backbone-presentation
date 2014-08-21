# reveal.js 

### HootSuite Theme
The deck includes a HootSuite theme that is set up as the primary theme. This can be changed, but why would you want to do that? 

A framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://lab.hakim.se/reveal-js/). [Now check out the full doc's on the original Github Repo](https://github.com/hakimel/reveal.js/)

reveal.js comes with a broad range of features including [nested slides](https://github.com/hakimel/reveal.js#markup), [markdown contents](https://github.com/hakimel/reveal.js#markdown), [PDF export](https://github.com/hakimel/reveal.js#pdf-export), [speaker notes](https://github.com/hakimel/reveal.js#speaker-notes) and a [JavaScript API](https://github.com/hakimel/reveal.js#api). It's best viewed in a browser with support for CSS 3D transforms but [fallbacks](https://github.com/hakimel/reveal.js/wiki/Browser-Support) are available to make sure your presentation can still be viewed elsewhere.

## Setup
* clone the repo
* Install all NPM modules with ```npm install```
* Run the local server ```grunt serve```
* Everything else is on the [original repo](https://github.com/hakimel/reveal.js/)

## For HootSuite

I've changed/added some things beyond the scope/features in the original documentation. 

* Include ```data-state="reverse"``` in your ```<section>``` where you define a slide if you want the reverse title slide
* Most everything else should work. But do you REALLY want to use full screen background gif's? Yes, yes I do!

### @TODO
* All the things should be anchored at the top of the page, and not in the middle