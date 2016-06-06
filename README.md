Heroku buildpack: Node.js with grunt support
============================================

EventCollab : Heroku Front-end buildpack
------------

Here's an overview of what this buildpack does:

- Caches node_modules
- Caches app/bower_components (currently disabled)
- Starts grunt process depending on the production status (Testing, Sass -> CSS compiling, Typescript -> JS transpiling, CSS/JS/HTML minifications)

