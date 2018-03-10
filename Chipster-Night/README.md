# "Chipster Night" pfSense WebUI Theme

## About / Info

This pfSense WebUI theme is a lightly modified version of the canned, "Dark Beta"
theme, shipped with pfSense 2.4.2:

### Features

* General UI:
  - Two selectable UI font sizes; large and smaller.
  - Consistent font family and sizes
  - Consistently-colored bar charts/progress bars
  - Consistently-colored status indicators and FontAwesome elements
  - Color tweaks and consistency for common UI element, tables, and other UI elements.

* Traffic Graphs:
  - Consistent stroke and fill colors with the rest of the theme 
  - Inverse graph mode follows a more "natural" traffic flow design:
  -- Inbound traffic flows "south" or downward
  -- Outbound traffic flows "north" or upward

## Installation
1. If you do not wish to install the Traffic Graph tweaks, skip to Step #4.
2. Copy the contents of the `js` folder to `/usr/local/www/js`
3. Copy the contents of the `vendor/d3` folder to `/usr/local/www/vendor/d3` (note: this will
   affect the color of the charts regardless of the theme selected, so you may want to make a
   backup of this file before proceeding.)
4. Copy the contents of the `css` folder to /usr/local/www/css`

## Screenshot:
![alt text](http://techdocs.cuccio.us/Chipster-Night_SS.png "Screenshot: Smaller Font CSS")

