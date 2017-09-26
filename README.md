# bootstrap-namespaced
Namespaced Twitter Bootstrap CSS

## What is this?

Twitter Bootstrap v4.0.0-beta compiled with a 'namespacing' class *.twbs*. (If you are interested, the process for an earlier version (v4.0.0-alpha.5) of Bootstrap 4 is described here: https://medium.com/@JonasJancarik/namespacing-bootstrap-css-419961f4d1f8 - not valid for v4.0.0-beta.)

## What is this good for?

For adding Bootstrap to an existing project and avoiding conflicts with existing CSS classes.

## How to use this?

Include the file bootstrap-ns.css (in dist/css) in your project like you would the usual Bootstrap CSS file, for example:

`<link rel="stylesheet" href="css/bootstrap-ns.min.css">`

Use Bootstrap as usual, but add the twbs class to the element under which you want Bootstrap CSS to be applied. To include the entire document, add it to the `HTML` tag, e.g.:

`<html class="twbs">`
