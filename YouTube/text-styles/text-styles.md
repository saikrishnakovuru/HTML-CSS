Refer the website https://supersimple.dev/exercises/text

## line-hight

Gives the spacing between the lines.
![Alt text](image.png)

## special characters

The special characters like dot and tick are called entities, we can google for `html entity dot` for teh dot we have a hexadecimal code `&#183;`.

## default margins in paragraphs

Paragraphs in HTML by default get some margin, which resulting in teh extra spacing while having 2 paragraphs one by one. We can manually override them giving our preferred margin like `margin-bottom: 5px`.

## CSS specificity

In text.html file we moved all the common styles of paragraphs to one place. However, the styles we write mentioning the class names has higher preference than the common selector.

If we give specific style to an element with its class name has the higher priority.

That means the selector that's more specific has higher priority.

> class name selector > element name selector.

specificity is nothing but pointing to the specific element by its class name.

## Underlining the text

`text-decoration: underline` --> underlines the text.

However, if we want to underline a specific part of the text we need something called `text element`

There are few text elements such as <strong></strong> that makes the text bold.

<span> is something that don't show any effect on the text however we can give it a class name and define the styles.
