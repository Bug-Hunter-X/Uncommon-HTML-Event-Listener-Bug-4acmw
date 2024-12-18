# Uncommon HTML Event Listener Bug

This repository demonstrates a subtle bug related to event listeners in HTML.  The issue lies in how the event listener is added to the element. The `addEventListener` method is used incorrectly resulting in the alert not firing.

The `bug.html` file contains the buggy code. The `bugSolution.html` file provides a corrected version.  The bug is demonstrated using a simple click event on a div element.

This example highlights the importance of correctly using the `addEventListener` method to ensure that events are handled appropriately.

## How to reproduce

1. Open `bug.html` in your browser.
2. Click on the div element.
3. Notice that the alert box does not appear.  This is due to the bug.

Now open `bugSolution.html` and repeat the steps. The alert should now appear correctly.