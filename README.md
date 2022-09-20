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

we want to give extra horzontal spacing to some text of 2nd p element, put the text inside span element with class name as right.

Now we want the span text aligned to right, we can do this easily with float property set to right in the .right element.

take all the content of .label element and put it inside header element, which will be immediate child of .label element.

Now specifically target h1 element, selector we need to use now is header h1, it applies to h1 element of the header element only.

Now what we want is a divider after header element, so add div element of class "divider lg" after header element.
with "divider" class, it will apply the css rules of divider selector which is to make a horizontal line which is already present in header element.
Now with lg class, give height of 10px, it will make space above it by pushing the line downwards.

Now with .lg and .md(will be used later in other div element) element, give background-color to black, which will result in a thin black horizontal line, but if we look it closely we will see a small border in grey color, to remove it, use border:0.

Add a new div element with class name "calories-info" after .lg element.

inside .calories-info element, add p element with class name "bold sm-text" and content of p element is "Amount per serving"
Here, what would happend is it will immediately apply the css rule of .bold selector which is font-weight of 800, which will make the content of p element in bold.

Now need to work with .sm-text element, rem is root em, so in here we have already provided html element font-size to 16px, realtive to the root element we can manipulate font sizes, so in sm-text, make font-size to 0.85rem which will be roughly around 13px.
So with 2 classes, we have set css rules to the new p element, one class is giving boldness and one gives font-size.

Add new h1 element immediately after sm-text p element, with text as Calories 230 and span the text 230 with class name right, which will use .right element css rule of float to right side.

Now select h1 element of calories-info div, .calories-info h1{}, and we want the content of h1 to be slightly up and slighlty strecthed sideways, to do that set margin in -ve, top and bottom to -5px and left, right to -2px.

Now need to select span element of .calories-info element and set the font-size of 1.2em: .calories-info span{}

Now the text 230 is outside of the box, to avoid this we can set overflow property to hidden, what it will do is push the box downside, and we need to set this property to h1 element of .calories-info element, .calories-info h1 {}.

Now comapred to the text of calories to 230's alignment, we see 230 is not in the right place, little downside, so we need to make it move little up with margin-top property set to -7px, so to make it possible, use .calories-info span selector as we want to manipulate span element which is 230.

below .calroies-info element, add a div element with class name "divider md" as it will inherit divider and md css rules, which is border-bottom of 1px solid black, top and bottom margin of 2px, background color black and no border.

Now, we need to give a height of 5px to the horizontal line, Add .md element in CSS, set height to 5px.

Add a new div element with class name "daily-value sm-text".
Add a p element with class "right bold" with text "% Daily Value *", it will inherit the css rules of right and bold which is flot to right and font-weight of 800.
Now add a new div element with class divider to add a horizontal line, which will inherit the rule of .divider element, which is 1px solid color and margin of 2px at top and bottom and 0 in sideways.


