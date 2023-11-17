Few styles for eye wash!

`color` --> Decides color to the text inside the button.

`border-radius` --> curved border.

`cursor` --> Styles the curser.

`opacity` --> Used to fadeout a component, usually used to fadeout on hover(on  
 hovering the buttons or links) and while the button is active(on clicking hte button).

## pseudo classes

pseudo classes gets applied on hovering(hover) or on clicking(active).

```html
.subscribe-button:hover { opacity: 0.8; }
```

```html
.subscribe-button:active { opacity: 0.8; }
```

## transition

Transition enables the smooth transitions which includes many actions one such thing is fading out the button by applying opacity.

Let's discuss an `use case` for example we applied opacity for a button on hovering, as soon as we hover the button the opacity immediately reflects, To make thet `smoother` transition property helps us in achieving that.

transition accepts two parameters one is what needs to te smoothened and the and the another one is how long the smooth transition should happen.

```html
transition: opacity 0.15s;
```
