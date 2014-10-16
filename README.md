combo-input
============

A combination polymer custom element that wraps built in polymer input types.

The polymer API style documenation on the combo-input are [here.](http://kwokoek.github.io/combo-input/components/combo-input/)

See polymer for more info at [polymer.](https://www.polymer-project.org/)

## Build it local

Make a root development folder, and clone this repository in it.

Now cd into the combo-input folder to build!

```
cd combo-input
bower install
```

Now we need to start a web server to serve up our demo page, which we need to run from one level up.

```
cd ..
python -m SimpleHTTPServer
```

Now point your browser at our demo page

`http://localhost:8000/combo-input/demo.html`


## Build from Bower
You can build the latest push from bower.

Create a new project folder, and initialize with bower

```
bower init
bower install --save combo-input
```

Now build a demo page using these includes in your html file:

`<script src="bower_components/platform/platform.js"></script>`

`<link rel="import" href="bower_components/combo-input/combo-input.html">`

Now you can use the custom element (see the demo.html page for more example usage)

`<combo-input id='combo2' title="My Second edit" edit_placeholder="Enter Color" checked_title="Favorite" checked=true ></combo-input>`



