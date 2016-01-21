 SVGPan library 1.2.2
======================

Given an unique existing element with id "viewport" (or when missing, the 
first g-element), including the the library into any SVG adds the following 
capabilities:

 - Mouse panning
 - Mouse zooming (using the wheel)
 - Object dragging

You can configure the behaviour of the pan/zoom/drag with the variables
listed in the CONFIGURATION section of the file, SVGPan.js.

Known issues:

 - Zooming (while panning) on Safari has still some issues

Releases:

1.2.2, Tue Aug 30 17:21:56 CEST 2011, Andrea Leofreddi
 - Fixed viewBox on root tag (#7)
 - Improved zoom speed (#2)

1.2.1, Mon Jul  4 00:33:18 CEST 2011, Andrea Leofreddi
 - Fixed a regression with mouse wheel (now working on Firefox 5)
 - Working with viewBox attribute (#4)
 - Added "use strict;" and fixed resulting warnings (#5)
 - Added configuration variables, dragging is disabled by default (#3)

1.2, Sat Mar 20 08:42:50 GMT 2010, Zeng Xiaohui
 Fixed a bug with browser mouse handler interaction

1.1, Wed Feb  3 17:39:33 GMT 2010, Zeng Xiaohui
 Updated the zoom code to support the mouse wheel on Safari/Chrome

1.0, Andrea Leofreddi
 First release
