AtelierJS
=========

--> [CreateJS family](https://github.com/CreateJS)

### Summary

_AtelierJS_ is essentially a framework on top of CreateJS, that adds an asset library (Souvenirs) and a scene manager (Curator) which allow you to write and switch/transition between self-contained Scenes. Scenes are JS objects with their own animation loop, 'DisplayList' and state machine. 

*If you come from a Flash development background, then this should all feel very famliar.*

To give you an idea of how it can be used take a look at the source of my [L'artiste Springboard template for HTML5 Canvas development](https://github.com/bloomingbridges/artiste) for the time being.

The API is still subject to changes, so use it at your own discomfort.

### What is still missing?

* Full Scene blueprint specification, loading mechanism and parsing (so Scenes can be authored via a 3rd party application)
* The possility to address multiple canvasses on a single page
* Presets for transitions between Scenes

### The specifics

Includes _js-signals_ and John Resig's _Simple inheritance_ model.