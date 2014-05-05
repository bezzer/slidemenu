Slide Menu
==========

A CSS based animated menu optimized for mobile devices

[View the demo](http://bezzer.github.io/slidemenu)

Structure
---------

The classes needed for the navigation menu to work are "window", "navigation" and "navigation-header". "window" is the content window that will be moved when the menu is openned, "navigation" is the list of navigation items that is revealed when the window is moved. The "navigation-header" class contains the menu open button and is fixed to the top of the page.

    <body>
        <div class="navigation">
            <ul>
                <li>Item one</li>
                <li>Item two</li>
                <li>Item three</li>
            </ul>
        </div>
        <div class="navigation-header slide">
            <a href="javascript:$('body').toggleClass('menu-open');">Open menu</a>
        </div>
        <div class="window slide">
            <!--Content goes here -->
        </div>
    </body>
