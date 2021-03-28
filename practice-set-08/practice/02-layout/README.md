# README

## CSS: Layouts with Grid

### Instructions

As you go through each step, I recommend checking the code in Firefox. If something is incorrect, you will find the mistake easier to catch if there is less code to review.

Like the `01-grid-basics` exercises, there is a corresponding example for each set of html/css files in this repository. Look at how the page is laid out and mimic this. Be sure to look at each HTML file to see what elements/ids you can use to apply these styles.

Other than correcting any validation errors, you **MAY NOT** change any of the HTML.

In all cases, your layout should be flexible! Be sure to use the correct properties and values to achieve this. Pay attention to detail -- such as whitespace (you will need to adjust box model properties in a couple cases) and content constraint (you will need to center each `#wrapper` within body).


#### Layout A

1. Set the header, nav and footer to have a background color of `#eee`.

2. Keep the entire layout constrained within 960px.

3. Use only grid line numbers to lay out the elements.

4. The header and footer should stretch across the width of the container. The nav will take up 1/3 of the container; the main 2/3.

5. Apply a 20px grid gap.

6. Adjust whitespace for the remaining content using box model properties.


#### Layout B

1. Set the header, nav and footer to have a background color of `#eee`.

2. Keep the entire layout constrained within 960px.

3. Use grid line numbers to lay out header, nav, main and footer. The nav will take up 1/3 of the container; the main 2/3.

4. Use a grid template to lay out the sections within main. The 'welcome' section will stretch the width of main; the remaining two will split the width of main equally.

5. Apply a 20px grid gap on all grids.

6. Adjust whitespace for the remaining content using box model properties.


#### Layout C

Lots to complete in this one!

1. Create a horizontal navigation. You do not necessarily need to use a grid here (you built a horizontal nav bar in a previous practice set), but you can! The spacing between each item doesn't need to be exact, but there should be spacing.

2. Set the header, nav and footer to have a background color of `#eee`.

3. Set the section(s) to have a background of `transparent` (this will overwrite the rule alreayd set in the css file).

4. Keep the entire layout constrained within 800px.

5. Use only a grid template to lay out the elements. (Do you have to use a grid on `#wrapper`? Or is there another, simpler way to accomplish this layout? Hint, hint.)
