# DAY2
1) Write a blog on the difference between document & window objects.
         document	                                              window
It is loaded inside the window.	               It is the very first object that is loaded in the browser.
It is the object of window property.           It is the object of the browse 
When JavaScript is executed inside the browser, the window object is the JavaScript Global object. The document object is a property of the window object.

The window object represents the browser window.
The document object represents the HTML document loaded in that window.

The window object has many useful properties like the location object and the setTimeout function.

Since the window object is the Global object, ergo, it is the end of all scope chains, you don’t have to explicitly specify it when accessing its properties…
Instead of window.setTimeout, you can just write setTimeout
Same goes with document… instead of window.
