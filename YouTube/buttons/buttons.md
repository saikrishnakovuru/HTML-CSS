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

## box-shadow

We added shadow to the Tweet button on hovering.

box-shadow helps us to add the shadow to the object
it has 4 values.
1-> horizontal position
2->Vertical position
3->Blur
4-> color.

As part of color we use rgba where a is the opacity.

```html
.tweet-button:hover { box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2); }
```