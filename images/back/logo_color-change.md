logo color can be changed for .svg type files with the use of filters property
in CSS but to know the excat value of the fliter can be a bit tricky.

To tackel this problem we just need the hex code of the color that we need to change
tolike in this case ##C91B28 then we need to go to the following link
[codepen](https://codepen.io/sosuke/pen/Pjoqqp)

copy the hexcode in  target color and click on "Compute Filters" button

it will generate the required filters to change the color to tragetted color
copy the filters to your CSS file and apply it your img using selectors
```CSS
.logo{
    filter: invert(17%) sepia(63%) saturate(5467%) hue-rotate(347deg) brightness(81%) contrast(93%);
}

