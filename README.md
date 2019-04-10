# canvas-where-am-I
Theme .js and .css to add within course navigation to Instructure Canvas. Does the following:

## Add Modules sub-menu
* Sub-menu item takes you to Modules page but hides other Modules
![Clicking on Module in menu shows only that Module](https://github.com/msdlt/canvas-where-am-I/blob/master/readme-images/sub-menu-shows-only-selected-module.png)
* For Pages and other items that are launched via the Modules page, the appropriate sub-Module will be highlighted in the list below Modules
![See containing Module](https://github.com/msdlt/canvas-where-am-I/blob/master/readme-images/sub-menu-shows-module-containing-page.png)
* Modules takes you to normal Modules view (unless it is the Home page)
![Modules works as normal](https://github.com/msdlt/canvas-where-am-I/blob/master/readme-images/modules-shows-normal-modules.png)

## Add tiles at top of Modules tool (ONLY if Modules is set as home page):
![Autogenerated tiles for home page](https://github.com/msdlt/canvas-where-am-I/blob/master/readme-images/autogenerated-module-tiles-and-navigation.png)
* Tiles are generated by calling the Canvas api
* Added a drop-down arrow which gives you a quick link to the Module item (page, discussion, etc) - NOTE: only if showItemLinks==1
* Clicking the tile anywhere except the drop-down arrow takes you to the appropriate part of the Modules page

## Add progress bar below content (between Previous and Next buttons) as either:
* icon buttons for each item in a Module, linking to that item
* if insufficient space for buttosn, show bar indivcting position through Module as %

## Copy Previous and Next buttons from bottom of page to top
* currently not working on every content type - see notes below
