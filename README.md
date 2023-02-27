# JS-Day-20-A
Drag N Drop

This code creates a simple drag and drop functionality.

The HTML code creates a page with several empty div elements, and one of them contains a child div that can be dragged. This is done by adding a draggable attribute to the child div.

The CSS code defines the appearance of the elements, and some classes that will be added or removed during the drag and drop process.

The JavaScript code handles the drag and drop events. When the user starts dragging the child div, its dragStart function adds a class to the div to indicate that it is being held. This function also sets a timeout of 0 seconds to hide the original div, since a copy of it will be created in the drop target.

During the drag, when the mouse pointer is over one of the empty divs, the dragEnter function adds a class to the empty div to indicate that it is a valid drop target. When the pointer leaves an empty div, the dragLeave function removes the class. When the user drops the child div into an empty div, the dragDrop function removes the class from the empty div, and appends the child div to it.

Finally, when the user finishes the drag operation, the dragEnd function removes the class from the child div, and restores its visibility.