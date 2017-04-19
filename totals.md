Using the following CSS code to complete each task. Save your written answer to a file called totals.md:
div{
    width: 321px;
    height:  422px;
    border: 2px solid green;
    margin-right: 10px;
    margin-bottom: 20px;
    padding:  20px 10px;
}
a) Using the Content Box model, calculate the "total" width and height of the div. Show your calculation and explain how you arrived at your answer.
Width: 345px, Height: 466px
The Content Box model only includes the content in the width calculation, but not the padding, border or margin. They have to be considered separately.  I don't consider the margin to be part of the total width of the element because it is outside the border.

b) Using the Border Box model, calculate the "total" width and height of the div. Show your calculation and explain how you arrived at your answer.
Width: 321px, Height 422px
The padding and border is included in the width calculation (but again, not the margin).
