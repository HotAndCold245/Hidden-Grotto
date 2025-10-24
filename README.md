# Introduction
This theme is primarily designed for personal use. The base color palette is inspired by the Pokemon, Clobbopus. 

#Note : The font used in the images for this theme is called Quicksand and can be found through Google Fonts. A snippet for the font is available in the theme's repository. 
![IMG_1](https://github.com/user-attachments/assets/5b480b0e-8515-418a-995a-c764ff6edb7d)

# Features
- Supports both **light** and **dark** mode
- Additional colour palettes
	- Available through the Style Settings plugin.
	- Also through the [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) plugin (Not currently available in the plugin store but can be accessed via the BRAT plugin).
- Updated callouts
	- Callout titles now come with a border below it.
	- Callouts icons are hidden but can be enabled again by setting `--grotto-callout-icon: auto`
- Updated embed
	- Titles are hidden but can be enabled again by using `.embed-title {display:block;}` in a snippet.
- Updated tables
	- Cells can now be separated or collapsed by using `--grotto-table-border-style: separate` or `--grotto-table-border-style: collapse`
	- Cell wrapping can be adjusted using `--grotto-table-cell-width`. Setting it to `fit-content` allows it to wrap around while `max-content` prevents cell wrapping. Optionally, a specific maximum width in px can be set
- Mobile toolbar
	- The maximum toolbar height (number of rows visible) can be adjusted by setting `--grotto-toolbar-rows` to the number of rows. If there are more tools than a row can hold while maximum height is set to 1, then the toolbar can be swiped up to access the rest of the tools. This is a change from the default behaviour of swiping to the left because it let's you see more of the tools at once. #Note : Setting the height to more rows than necessary to hold the active number of tools will cause the mobile toolbar to move further up than intended. 
- Mobile navbar
	- The view actions (reading/editing toggle and more options) have been moved to the bottom for easier reach. Additionally, the file path has been hidden for extra room. 

# Screenshots
![IMG_2](https://github.com/user-attachments/assets/52056adc-e39f-4b01-8764-f0f7388be70e)
![IMG_3](https://github.com/user-attachments/assets/ed458c15-75f8-4459-b4d5-2aaacf782252)
![IMG_4](https://github.com/user-attachments/assets/00b3d483-f37d-4233-8abb-ad518b037148)
![IMG_5](https://github.com/user-attachments/assets/5935bd50-73eb-4543-bab0-d88d646ea786)

# The Plugin
 The [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) plugin developed for use with this theme allows for more customization. Color palettes can be easily swapped between using a dedicated ribbon/toolbar/command prompt button. You can also create your own presets using the following format.
 ```
.preset-yourpresetname {
    --accent-h: ;
    --accent-s: %;
    --accent-l: %;
    --grotto-day-1: hsl(); /*Controls the background color in light and text in dark mode*/
    --grotto-day-2: hsl(); /*Controls the hover color for certain menus in light mode*/
    --grotto-night-0: hsl(); /*Controls the sidebar color in dark mode*/
    --grotto-night-1: hsl(); /*Controls the background color in dark mode*/
    --grotto-night-2: hsl(); /*Controls the hover color for certain menus in dark mode*/
    --grotto-accent-1: hsl(); /*Accent color*/
    --grotto-accent-2: hsla(); /*Accent hover*/
}
 ```
Self-defined presets will automatically appear in the Hidden Grotto Controls plugin menu after restarting the app. #Note : These will not appear in Style Settings menu since they are not added to the main theme.css. 

# Feedback
Please submit an issue on the repository or try the discord server.

# Changelog
##### V1.1.2
- Fixed default behaviour of table cells - Now set to wrap around
- Fixed default behaviour of embed titles - Now set to be visible
##### V1.1.1
- Fixed readable line width controls
##### V1.1.0
- Added Style Settings support
