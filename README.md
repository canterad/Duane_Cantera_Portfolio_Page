# 01-HTML-Git-CSS-Homework
This repository was created for the Homework Assignment dealing with Advanced CSS.

Developer: Duane Cantera
Date: Sept. 25, 2021
Assignment: 02 Advanced CSS: Portfolio

I built my own Portfolio page.

****************
PAGE LAYOUT:
****************

The layout of the web page has been broken up into to sections.  The title section is on the left side of the page and the data section is on the right.  I created sections that are relative parents so the title and data items can be position there and they will not move when the
display block next to it changes its size.

< Header Section >
    < Section - Header Title >
    < Section - Header Data Relative Parent >
    < Section - Header Data Block >
    < Section - Header Data >
        < Navigation Section >

< Main Section - About Me Title Relative Parent >
    < Section - About Me Title Block >
    < Section - About Me Title >
    < Section - About Me Data>

< Section - Work Relative Parent >
    < Section - Work Title Block >
    < Section - Work Title >
    < Section - Work Data >
        < Section - Featured Work >
        < Section - Work Row 1>
            < Sub-Work Item 1 >
            < Sub-Work Item 2 >
        < Section - Work Row 2 >
            < Sub-Work Item 3 >
            < Sub-Work Item 4 >

< Footer Section - Contact Me Relative Parent >
    < Section - Contact Me Title Block >
    < Section - Contact Me Title >
    < Section - Contact Me Data >
        < Navigtation Section >


*********************
DEVELOPMENT ISSUES:
*********************

Issue: Inline blocks next to one another inside a container - One would move when the size of other one changes:

Solution: I found that I had to create a relative parent container and then I could position the child absolute and the child element
would be positioned where the parent container is located and would not move when the inline block next to it changes size.


***************************
RESPONSIVE DESIGN ISSUES:
***************************

Issue: My photo would continue to shrink when I resized the browser window.
Solution: I used Meta Queries at intervals of 75 pixels and I updated the max width of the photo by increasing it by 10 pixels.

    
Issue: Size of elements changing when the browser window was resized.
Solution: For most of my elements I used percentages instead of pixels when declaring width values.

Issue: Controlling how links were displayed in the navigation sections.
Solution: In the unordered lists elements I used a flexbox with the flex direction set to row with no wrap.
          I used no wrap because I did not like the way the links were layed out when wrapping occurred.
          When the links got too close together I change the flex direction to column.

Issue: Contolling the layout of the Header Title elements, My name, Photo and Job Title.
Solution: In the Header Title section I used a flexbox and set the flex direction to column, no wrap and spaced evenly
          so the layout of the elements would stay the same when the browser window was resized.

Issue: Controlling how the sub work items are layed out when the browser window is resized.
Solution: In the Work Order Rows I used a flexbox with the flex direction set to row with wrap turn on and space between content.


***************
LINKS:
***************

Link To Deployed Application: https://canterad.github.io/Duane_Cantera_Portfolio_Page/
# Duane_Cantera_Portfolio_Page