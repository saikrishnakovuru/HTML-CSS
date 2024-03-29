Few styles for eye wash!

In this file we are creating the buttons to look like in the below website
https://supersimple.dev/exercises/buttons

`color` --> Decides color to the text inside the button.

`border-radius` --> curved border.

`cursor` --> Styles the curser.

`opacity` --> Used to fadeout a component, usually used to fadeout on hover(on  
 hovering the buttons or links) and while the button is active(on clicking hte button).

`border-width` --> Border looks thicker without the border width.

## Border style

With out the border style we will notice a weird border color,though we set a color to the border top and left sides of the border gets decorted with the color we set. However, right and botton gets different color. To overcome this border-stype helps us.

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

## CSS Box model instead of hight and width

In real world the requirements may change ant any point of time, if we give a fixed size(using hight and width) to a button anticipating it has the small name would not be suitable when the name of the button gets changed. If the name is bigger than the width we gave if overflows like in the below image.

![Alt text](image.png)

Always we shoulud go for box-model i.e using padding, border and margin.

Padding is the right alternate to hight and width.

Every element has the spacing outside which is margin and spacing inside which is padding.

## vertical-align

Look at the below image

![Alt text](image-2.png)

Buttons borders are litte dealighned as we added paddding to JOIN button but the `text is on the same line for all the 3 buttons` this is because the web pages are text aligned.

To override this behaviour and want to have everything on top we need a css property called `vertical-align: top`

![Alt text](image-1.png)

## In buttons-exercise

> importance of `vertical-align: top`

I added two buttons stretch and 3dClick, gaven the below styles for 3dClick

```java
     .three-dimention-button:active {
        margin-top: 3px;
        margin-left: 3px;
    }
```

With the above styling the button moves a little on clicking. Action works perfectly well however, the stretch button also started acting weird by moving away on cliking the 3dClick button.

I got stricked by the point that web pages are text aligned and I added `vertical-align: top;` which resolved the problem.
