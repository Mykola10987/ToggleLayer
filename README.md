Changes the inner HTML for the element after the event

### Using:

- Copy the code from the togglelayer.js file and paste it into your source;
- In your code, create a new instance of the class with attributes

```javascript

let q = new ToggleLayer({
	el {Element} - element where the layers change
 	layer {HTML || [HTML]} - layers to replace
 	false || loop {Boolean} - repeat after completion
 	'click' || e {string}
		'hover' - change layers only when hovering on attr.el
		'click' - change layer after click
		'loaded' - change layers immediately after loading
 	0 || fade {number} - fade effect when changing the layer
 	0 || delay {number} - delay before change
})

// start changing layers
q.toggle(true)

// stop changing layers
q.toggle(false)

// add layer
q.add_layer(html)

// stop using
q.stop()
```
