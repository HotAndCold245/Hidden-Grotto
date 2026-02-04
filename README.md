# Changelog
<details>
	<summary>v.1.5.100</summary>
- #New - Added option to hide most borders via Style Settings
- The theme is now fully updated for the latest version of Obsidian
- Upcoming additions (and a reminder to myself) - Hidden UI elements, more color presets, add font directly to the theme

</details>


# Introduction
This is a theme I primarily made for personal use. It focuses on a clean and sharp design with some modifications to the default UI, especially on mobile, for a better experience. The base color palette is inspired by the Pokemon, Clobbopus. 
![IMG_1](https://github.com/user-attachments/assets/6a667c1f-cd96-45b4-acce-3020b211a49f)

# Features
- Support for both **light** and **dark** mode
- **24** color palettes to choose from through **Style Settings** or from [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) (Available through BRAT)
- Updated **mobile toolbar** with vertical scrolling
- Updated **callouts** with hidden icons which can be reenabled by setting `--grotto-callout-icon: auto`
- Option to **blur** or **redact** everything to provide some privacy when notes are left unattended
	- #Note : Only use this feature if you know how to navigate to the settings to disable it

# Screenshots
#Note : The font used in the images for this theme is called Quicksand and can be found through Google Fonts. A snippet for the font is also available in the theme's repository. It's not part of the theme. 

<details>
	<summary>Color Palettes</summary>

![Absol](https://github.com/user-attachments/assets/16c87b65-0ab2-4341-b272-96bc0f6b63ee)
![Aegislash](https://github.com/user-attachments/assets/489987c0-ef0c-43a8-9fa3-80091a951265)
![Aggron](https://github.com/user-attachments/assets/2167f4d8-fdf4-438d-9b61-9f542dfbea2f)
![Calyrex](https://github.com/user-attachments/assets/593c8a2d-f6fe-4aef-97b2-ba822de2733d)
![Clobbopus](https://github.com/user-attachments/assets/2515dcd0-f700-46e7-bbf8-0408bfbc2ff4)
![Darkrai](https://github.com/user-attachments/assets/58a00b23-7931-41c4-ab08-b11c90217748)
![Lucario](https://github.com/user-attachments/assets/6156ea3a-e607-4905-851a-99d1a164e517)
![Meloetta](https://github.com/user-attachments/assets/c6b8c6df-f21a-4be0-8536-d9468ae4de46)
![Poltchageist](https://github.com/user-attachments/assets/27540fce-8627-483a-9b5e-f681edb2c051)
![Rayquaza](https://github.com/user-attachments/assets/f05234d7-6b13-4f48-aca8-809f1ac5306d)
![Scolipede](https://github.com/user-attachments/assets/e852eeaa-f526-46b8-ac5e-5d24dfaa1d39)
![Swampert](https://github.com/user-attachments/assets/5c9eff61-53c4-4dfe-b9bb-b1a610dfd6f9)
![Ursaluna](https://github.com/user-attachments/assets/66721c31-93ac-4eed-827d-ba567630e191)
![Volcarona](https://github.com/user-attachments/assets/1a276767-cbb7-4d56-bd4b-8053becdf60d)
	
</details>

<details>
	<summary>Mobile Toolbar</summary>

![Toolbar](https://github.com/user-attachments/assets/ffa4cded-2d98-4d47-9300-1062eede1fb6)

</details>

<details>
	<summary>Blur</summary>

![Blur](https://github.com/user-attachments/assets/18d4c412-cba2-4f0b-8046-972b4ea0b86d)

</details>

# Color Presets
You can create your own color preset using the following format in a snippet.
```
.preset-yourpresetname {
	--accent-h: ;
	--accent-s: ;
	--accent-l: ;
	--grotto-light-1: hsl();
	--grotto-light-2: hsl();
	--grotto-light-3: hsl();
	--grotto-dark-0: hsl();
	--grotto-dark-1: hsl();
	--grotto-dark-2: hsl();
	--grotto-accent: hsl();
}
```
If you are using the **Hidden Grotto Controls** plugin, your preset will be automatically added to the list of presets. In the case of **Style Settings**, you will need to add the following format to the snippet as well. 
```
/* @settings
name: Personal Presets
id: personal-presets
collapsed: false
settings:
    -
        id: color-palette
        title: Personal Presets
        type: class-select
        allowEmpty: true
        options:
            -
                label: Your Preset Name
                value: preset-yourpresetname
*/
```
You can include additional changes to your preset using the variables declared by the theme. A full list of variables can be found in the theme.css file.
#Note : The presets included in the theme are always subject to change. 

# The Plugin
The [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) plugin includes all the settings available in **Style Settings** as well as an easy way to cycle through the presets and toggle blur through ribbon commands. There's no need to use it if you don't need the shortcuts. 

# Feedback
If there are any problems with the theme, you can submit an issue on the repository or try the official Obsidian discord server in the #appearance channel.
