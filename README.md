# Introduction
This theme is primarily designed for personal use. The base color palette is inspired by the Pokemon, Clobbopus. 
![IMG_1](https://github.com/user-attachments/assets/6a667c1f-cd96-45b4-acce-3020b211a49f)
# Features
- Supports both **light** and **dark** mode
- 23 colour palettes
	- Available through the Style Settings plugin.
	- Also available through the [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) plugin (Not currently available in the plugin store but can be accessed via the BRAT plugin).
- Updated callouts
	- Callout titles now come with a border below it.
	- Callouts icons are hidden but can be enabled again by setting `--grotto-callout-icon: auto`
- Updated embeds
	- Titles are hidden but can be enabled again by using `--grotto-embed-title: block` in a snippet.
- Updated tables
	- Cells can now be separated or collapsed by using `--grotto-table-border-style: separate` or `--grotto-table-border-style: collapse`
	- Cell wrapping can be adjusted using `--grotto-table-cell-width`. Setting it to `fit-content` allows it to wrap around while `max-content` prevents cell wrapping. Optionally, a specific maximum width in px can be set
- Mobile toolbar
	- The maximum toolbar height (number of rows visible) can be adjusted by setting `--grotto-toolbar-rows` to the number of rows. If there are more tools than a row can hold while maximum height is set to 1, then the toolbar can be swiped up to access the rest of the tools. This is a change from the default behaviour of swiping to the left because it let's you see more of the tools at once. #Note : Setting the height to more rows than necessary to hold the active number of tools will cause the mobile toolbar to move further up than intended. 
- Mobile navbar
	- The view actions (reading/editing toggle and more options) have been moved to the bottom for easier reach. Additionally, the file path has been hidden for extra room.

# Screenshots
#Note : The font used in the images for this theme is called Quicksand and can be found through Google Fonts. A snippet for the font is also available in the theme's repository. 
![Absol](https://github.com/user-attachments/assets/16c87b65-0ab2-4341-b272-96bc0f6b63ee)
![Aegislash](https://github.com/user-attachments/assets/489987c0-ef0c-43a8-9fa3-80091a951265)
![Alola](https://github.com/user-attachments/assets/e5ae3e72-020d-46ca-ac9f-813b223e3610)
![Calyrex](https://github.com/user-attachments/assets/593c8a2d-f6fe-4aef-97b2-ba822de2733d)
![Cheren](https://github.com/user-attachments/assets/d7bd383b-beff-4b03-a8a0-3bb286418ca4)
![Clobbopus](https://github.com/user-attachments/assets/2515dcd0-f700-46e7-bbf8-0408bfbc2ff4)
![Darkrai](https://github.com/user-attachments/assets/58a00b23-7931-41c4-ab08-b11c90217748)
![Dawn](https://github.com/user-attachments/assets/20a76729-af39-42b2-abb5-54d0f8fddff6)
![Lucario](https://github.com/user-attachments/assets/6156ea3a-e607-4905-851a-99d1a164e517)
![Meloetta](https://github.com/user-attachments/assets/c6b8c6df-f21a-4be0-8536-d9468ae4de46)
![Noivern](https://github.com/user-attachments/assets/76cb067d-9f6f-456d-b04c-82e80a87c432)
![Poltchageist](https://github.com/user-attachments/assets/27540fce-8627-483a-9b5e-f681edb2c051)
![Rayquaza](https://github.com/user-attachments/assets/f05234d7-6b13-4f48-aca8-809f1ac5306d)
![Revavroom](https://github.com/user-attachments/assets/ee09d798-3b1a-4449-805a-fe22263eee47)
![Scolipede](https://github.com/user-attachments/assets/e852eeaa-f526-46b8-ac5e-5d24dfaa1d39)
![Skeledirge](https://github.com/user-attachments/assets/9cd44a27-6d6a-46fd-b20d-eed983640383)
![Steelix](https://github.com/user-attachments/assets/240c25b4-9cc2-43a0-81ea-0b2fb3d5081a)
![Swampert](https://github.com/user-attachments/assets/5c9eff61-53c4-4dfe-b9bb-b1a610dfd6f9)
![Unova](https://github.com/user-attachments/assets/dc194375-3ca1-4f2d-90fa-bc1b0f27e5d0)
![Ursaluna](https://github.com/user-attachments/assets/66721c31-93ac-4eed-827d-ba567630e191)
![Volcarona](https://github.com/user-attachments/assets/1a276767-cbb7-4d56-bd4b-8053becdf60d)
![Whimsicott](https://github.com/user-attachments/assets/7c18a816-3e85-4871-b79f-9cbfc4da4d13)
![Zacian](https://github.com/user-attachments/assets/5001d860-c99d-44ab-8131-30755cf3acde)

# The Plugin
 The [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) plugin developed for use with this theme allows for more customization. Color palettes can be easily swapped between using a dedicated ribbon/toolbar/command prompt button. You can also create your own presets using the following format. 
 ```
.preset-yourpresetname {
    --accent-h: ;
    --accent-s: %;
    --accent-l: %;
    --grotto-day-1: hsl();
    --grotto-day-2: hsl();
	--grotto-day-3: hsl();
    --grotto-night-0: hsl();
    --grotto-night-1: hsl();
    --grotto-night-2: hsl();
	--grotto-night-3: hsl();
    --grotto-accent-1: hsl();
    --grotto-accent-2: hsl();
}
 ```
There are more variables to control minor things that can be found in the css file.

Self-defined presets will automatically appear in the Hidden Grotto Controls plugin menu after restarting the app. 
#Note : These will not appear in Style Settings menu since they are not added to the main theme.css. In order to make them appear in the settings, you can add the following section to your snippet and update the `hoenn` parts to the name of your preset.
```
/* @settings
name: Personal Presets
id: personal-presets
collapsed: false
settings:
    -
        id: color-palette
        title: Presets
        type: class-select
        allowEmpty: false
        default: preset-hoenn
        options:
            -
                label: Hoenn
                value: preset-hoenn
*/
```

# Feedback
If there are any problems, you can submit an issue on the repository or try the official Obsidian discord server in the #theme-dev or #appearance channel. 

# Changelog
##### V1.3.0
- Added alternate Calendar Plugin style
- Added option to invert sidebar color
- Added preset - Whimsicott
