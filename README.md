# css_units
Testing css units


## em unit
The em unit use the current font-size. 
1em: is the same as the font-size of the current element.

Example:

if the font-size defined in the html tag is 14px and we apply a font-size of "1.2em" a p tag, for example, we will have the following font-size:

14px * 1.2 = 16.8px

## rem unit
rem: The rem (root em) works in exactly the same way as the em, except that it will always equal the size of the default base font-size; inherited font sizes will have no effect

## vw and vh unit
vw, vh: Respectively these are 1/100th of the width of the viewport, and 1/100th of the height of the viewport. Again, these are not as widely supported as rems.

## vmin and vmax 
While vh and vm are always related to height and width of the viewport, respectively vmin and vmax are related to the maximum or minimum value, widths and heights depending on which is smaller and bigger.

Just to clarify: 1vmax equals 1vh in portrait mode, whilst in landscape mode, 1vmax will equal 1vw

Example:

My notebook viewport has 672px x 1366px. So 100vmin is equals 672px (minor value of viewport) and, 50vmax is equals 683px (50% of 1366px).


# References

- [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Values_and_units)
- [Desenvolvimentoparaweb](http://desenvolvimentoparaweb.com/css/unidades-css-rem-vh-vw-vmin-vmax-ex-ch/)
- [Web-design-weekly](https://web-design-weekly.com/2014/11/18/viewport-units-vw-vh-vmin-vmax/)