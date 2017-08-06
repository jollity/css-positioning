# Positioning in CSS

## static

The **default positioning** for all elements is **position:static**, which means the element is **not positioned** and occurs where it **normally** would in the document.

*Normally you wouldn't specify this unless you needed to override a positioning that had been previously set.*

## relative

If you specify **position:relative**, then you can use **top or bottom, and left or right** to **move the element relative to where it would normally occur** in the document.  

Notice the space where the div normally would have been if we had not moved it: **now it is an empty space**.   
The next element (div-after) **did not move** when we moved the previous div.   
That's because the **previous div still occupies** that original space in the document, even though we have moved it.

## absolute

When you specify **position:absolute**, the element is **removed from the document** and placed **exactly where you tell it to go**.  

    #div-1a {
     position:absolute;
     top:0;
     right:0;
     width:200px;
    }

Notice that this time, since div-1a was **removed from the document**, the other elements on the page were **positioned differently: div-1b, div-1c, and div-after moved up since div-1a was no longer there**.

Also notice that div-1a was positioned in the top right corner of the page. It's nice to be able to position things related to the page, but it's of limited value.
