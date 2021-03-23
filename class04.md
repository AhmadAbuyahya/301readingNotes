# CSS Grid
* CSS Grid Layout (aka “Grid”), is a two-dimensional grid-based layout system that aims to do nothing less than completely change the way we design grid-based user interfaces.
* To get started you have to define a container element as a grid with display: grid, set the column and row sizes with grid-template-columns and grid-template-rows, and then place its child elements into the grid with grid-column and grid-row. Similarly to flexbox, the source order of the grid items doesn’t matter.
* Grid Container
The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container
 is the grid container.
* Grid Line
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.
* Grid Track
The space between two adjacent grid lines. You can think of them like the columns or rows of the grid.
* Grid Area
The total space surrounded by four grid lines. A grid area may be composed of any number of grid cells.
* Grid Item
The children (i.e. direct descendants) of the grid container.
* Grid Cell
The space between two adjacent row and two adjacent column grid lines. It’s a single “unit” of the grid.
# Regex
* Regular expressions (regex or regexp) are extremely useful in extracting information from any text by searching for one or more matches of a specific search pattern (i.e. a specific sequence of ASCII or unicode characters).
* Basic topics
Anchors — ^ and $
^The        matches any string that starts with The -> Try it!
end$        matches a string that ends with end
^The end$   exact string match (starts and ends with The end)
roar        matches any string that has the text roar in it
Quantifiers — * + ? and {}
abc*        matches a string that has ab followed by zero or more c -> Try it!
abc+        matches a string that has ab followed by one or more c
abc?        matches a string that has ab followed by zero or one c
abc{2}      matches a string that has ab followed by 2 c
abc{2,}     matches a string that has ab followed by 2 or more c
abc{2,5}    matches a string that has ab followed by 2 up to 5 c
a(bc)*      matches a string that has a followed by zero or more copies of the sequence bc
a(bc){2,5}  matches a string that has a followed by 2 up to 5 copies of the sequence bc
