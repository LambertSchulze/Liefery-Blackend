<img src="https://raw.githubusercontent.com/LambertSchulze/Liefery-Blackend/master/README%20Assets/Liefery_Logo.png" align="right" width="150" />

# Liefery-Blackend
Custom [Stylus](https://github.com/openstyles/stylus)-theme for the Backend at Liefery.

## Overview
This repository features two custom styles for the in-house software at [Liefery](www.liefery.com). These are CSS files that can be used in browser extensions that run custom CSS (like Stylus does).

### `layout.css`
The stylesheet in `layout.css` alteres the layout in *tour-schedule-plan* and *fast-dispatch* pages. It radically disables information that is not used for the task at hand and pushes information and menus that are used rarely to under the fold.
This dramatically speeds up the tasks of optimasation and disposition, wich both are time critical.

#### Tour-schedule-plan changes
- as much screen space as possible is used for map and tour list
- main navigation is hidden (not needed during workflow)
- information about the schedule plan is hidden (not needed during workflow)
- calculate button sticks to top

#### Fast-dispatch changes
- as much screen space as possible is used for map, courier company selection and tour list
- courier selection is hidden (nearly never used during workflow)
- information about tour and save button got pushed under the fold

### `darkmode.css`
The stylesheet in `darkmode.css` is a darkmode that uses the [Nord color scheme](https://www.nordtheme.com/).

In adition, the following functionality is changes:
- main navigation sticks to the top
- language selector (in the bottom right) is hidden
- back-to-top button sticks to the bottom right
- transition effects are turned off, which caused some usability issues by reentering the mouse to a disappearing mega menu

## Installation for Chrome
You can find a [installation guide](https://github.com/LambertSchulze/Liefery-Blackend/discussions/6#discussion-1707510) for the Chrome Browser in german in the discussions section of thes repository.
