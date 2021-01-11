<img src="https://raw.githubusercontent.com/LambertSchulze/Liefery-Blackend/master/README%20Assets/Liefery_Logo.png" align="right" width="150" />

# Liefery-Blackend
Custom [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)-theme for the Backend at Liefery.

## UI changes
Copy and paste the `darkmode.css` into Stylus for darkmode. The color palette used is the [Nord color scheme](https://www.nordtheme.com/).

In adition, the following functionality is changes:
- main navigation sticks to the top
- language selector (in the bottom right) is hidden
- back-to-top button sticks to the bottom right

**Note:** adding the style for the whole *liefery.com* domain messes up the colors on the homepage, fulfillment app and staging webpages.

## UX changes
Copy and paste the `layout.css` into Stylus for alternative layout in *tour-schedule-plan* and *fast-dispatch* pages.

#### Tour-schedule-plan changes
- as much screen space as possible is used for map and tour list
- main navigation is hidden (not needed during workflow)
- information about the schedule plan is hidden (not needed during workflow)
- calculate button sticks to top

#### Fast-dispatch changes
- as much screen space as possible is used for map, courier company selection and tour list
- courier selection is hidden (nearly never used during workflow)
- information about tour and save button got pushed under the fold

**Note:** if a specific courier must be selected, deactivate the Stylus theme by right clicking on the extension icon in google chrome.
