# Positioning in CSS

## static

The **default positioning** for all elements is **position:static**, which means the element is **not positioned** and occurs where it **normally** would in the document.

*Normally you wouldn't specify this unless you needed to override a positioning that had been previously set.*

## relative

If you specify **position:relative**, then you can use **top or bottom, and left or right** to **move the element relative to where it would normally occur** in the document.  

Notice the space where the div normally would have been if we had not moved it: **now it is an empty space**.   
The next element (div-after) **did not move** when we moved the previous div.   
That's because the **previous div still occupies** that original space in the document, even though we have moved it.
