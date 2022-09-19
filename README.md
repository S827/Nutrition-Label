# Nutrition-Label

Add h1 element with its content.

Add p element with its content.

Add another p element with its content.

Import Open Sans font family inside link element with rel as stylesheet and href with link

add link element in head element with rel as stylesheet and href as style.css

select body element in css and give font-family as Open sans with a fallback value of sans-serif.

Select html element in css and give font-size of 16px.

Add div element with class label and put h1 and both p elements inside .label

give border of 2px solid black to .label 

give width of 270px to .label.

Now the box(.label) is at the top left side of the screen, make it center with margin property 20px auto.

give padding of 0 7px to .label element.

We assigned .label with 270px width, but now with border and padding, it is 288px now,so to fix the width we need to use box-sizing property with border-box as its value in the * selector.

Make the h1 heading font weight more bolder with font-weight proprty set to 800 in h1 selector.

Align h1 to center

give outside space of h1 with margin property -4px at top and bottom and 0 at left and right.

select p element and remove margins.

add div element with class name divider below h1 element.

select .divider element in css and give border-bottom property a value of 1px solid color.
Now we need to make some space around divider element, left and right margins are not needed, only top and bottom margins does, so give top and bottom margin of 2px.

Now we want to give some space around h1 letters, we have a letter-spacing property, so in h1 selector, give letter-spacing a value of 0.15px.

Now we want multiple text to be bold at the same font-weight, to do this add a class of bold in 2nd p element and select it in css.
inside .bold, give font-weight value of 800;
as now we have .bold selector to make the text bold with a value of 800 as font-weight, now we can remove font-weight property from h1 selector and add a bold class in h1 element to make the text bolder at 800.



