# module3-solution
Coursera course: HTML, CSS, and Javascript for Web Developers (Module3)

# navbar 
- invisible and is not fixed to the top when you scroll the page down
- have a company name (i.e., navbar-brand class) called "Food, LLC" that is aligned to the **left side** of the navbar.
## Desktop and tablet view
- the navbar should not contain anything else. No other buttons should be visible. (Hint: use 'visible-xs' class.)
## Mobile View
- Create a simple menu button (3 horizontal bars). When the user clicks that button, a dropdown menu should appear (as illustrated in Mobile Open Menu illustration below.) The dropdown menu should contain 3 items: Chicken, Beef, and Sushi.
- Style 
    - The dropdown menu should take up the entire width of the browser window. Make sure the dropdown menu has a background color set that distinguishes it from the rest of the content.
# Main Content 
## Page Heading
- Our Menu should be centered within the browser window. You must use a Bootstrap class to accomplish this.
- Hint: look for a Bootstrap class that centers text, see https://getbootstrap.com/docs/3.3/css/#type-alignment.
## Body 
- Create a single really tall section that will use the Bootstrap Grid and take up the entire width of the browser window (minus some margins, of course) for all views: desktop, tablet, and mobile.
    - To make the section really tall, you can either fill it out with a LOT of text or simply set its height to something like 1000px. It needs to be tall enough to cause scrolling down to be required to view the bottom of the section.
    - Make sure its background color is set to distinguish it from the rest of the content.
        - Hint: don't forget to have an element with a class='container' or class='container-fluid' wrapping your grid. Remember that to have the grid do something "always", i.e., no matter what browser window size, use the col-xs-... classes. In this case, since we want the section to take up the entire row, use col-xs-12.)
