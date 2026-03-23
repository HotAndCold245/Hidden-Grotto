# Changelog
<details>
	<summary>v2.0.8</summary>

- Added automatic detection for the Quicksand font so it is no longer necessary to manually set it from appearance. Simply enable the font snippet. Only works for any font nicknamed 'Quicksand'. 
- Increased the font-size for RTL languages. Arabic is now easier to read. Only works while in editing mode.

</details>

# Introduction
This is a theme I primarily made for personal use. It focuses on a clean and sharp design with some modifications to the default UI, especially on mobile, for a better experience. The base color palette is inspired by the Pokemon, Clobbopus. 
![IMG_1](https://github.com/user-attachments/assets/6a667c1f-cd96-45b4-acce-3020b211a49f)

# Features
- Support for both **light** and **dark** mode
- **28** color palettes to choose from through **Style Settings** or from [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) (Available through BRAT)
- Updated **mobile toolbar** with vertical scrolling
- Updated **callouts** with hidden icons which can be reenabled by setting `--grotto-callout-icon: auto`
- Option to **blur** or **redact** everything to provide some privacy when notes are left unattended
	- #Note : Only use this feature if you know how to navigate to the settings to disable it

# Screenshots
#Note : The font used in the images for this theme is called Quicksand and can be found through Google Fonts. A snippet for the font is available [here](https://github.com/HotAndCold245/Hidden-Grotto/blob/main/Font/Font%20-%20Quicksand.css). It's not part of the theme because I wanted to keep the font usable without needing the theme. 

<details>
	<summary>Color Palettes</summary>

![Absol](https://github.com/user-attachments/assets/20445341-5074-4fbe-8721-65e4624ca397)
![Aegislash](https://github.com/user-attachments/assets/f67e4754-703b-4836-8610-bebc0fba585f)
![Aggron](https://github.com/user-attachments/assets/feb2359f-06ca-4eb0-8dab-a2b581052427)
![Aromatisse](https://github.com/user-attachments/assets/58d77442-418e-4aee-856c-c05934b31f9f)
![Butterfree](https://github.com/user-attachments/assets/cab5814a-0539-4262-be47-ec814fac5f07)
![Calyrex](https://github.com/user-attachments/assets/70702c70-a359-478b-93cc-cbccd92425ba)
![Clobbopus](https://github.com/user-attachments/assets/95fe1146-d493-4709-b29e-22fe2cf3344f)
![Cryogonal](https://github.com/user-attachments/assets/9f2a1e0a-9d60-4900-8e9e-bbeeafc0aacc)
![Darkrai](https://github.com/user-attachments/assets/5999cfeb-57e1-40e8-b7eb-aa4430dbe888)
![Dewpider](https://github.com/user-attachments/assets/8ea9c37c-cdd3-4a6a-bad8-f875d495ba46)
![Diancie](https://github.com/user-attachments/assets/4fe4604b-f3bc-47c2-8222-a1772608d161)
![Eldegoss](https://github.com/user-attachments/assets/306b4365-970d-4988-ad63-c6366c38d68a)
![Hisuian Typhlosion](https://github.com/user-attachments/assets/1d2271e6-450a-4391-8f57-03dbcf221d2b)
![Krookodile](https://github.com/user-attachments/assets/87009757-a168-4e11-8fca-0c16f520c219)
![Larvesta](https://github.com/user-attachments/assets/86b5206e-e389-4882-a7fc-77198ba2defb)
![Manectric](https://github.com/user-attachments/assets/c0f14758-55a3-4871-a679-772b254c4395)
![Mareep](https://github.com/user-attachments/assets/86f96a13-52b6-4113-a9f0-e9d9baa66165)
![Mega Lucario](https://github.com/user-attachments/assets/e7a1b5d2-45a4-426a-bd59-5ab7f3a3cfc9)
![Meloetta](https://github.com/user-attachments/assets/78eb671f-8803-4d67-be32-7d4babbc16b8)
![Necrozma](https://github.com/user-attachments/assets/efa670bf-8965-45d9-b9e9-ed2797c18868)
![Pirouette Meloetta](https://github.com/user-attachments/assets/c23b3df9-4c03-42f0-8f71-8ff547d3d72c)
![Poltchageist](https://github.com/user-attachments/assets/03d93f7a-76f9-4997-9a53-dff139093fff)
![Scolipede](https://github.com/user-attachments/assets/8851d93a-2b79-435b-850f-bfb7ea9a7219)
![Skiddo](https://github.com/user-attachments/assets/59a2b51f-cf04-4d37-bee3-1c725a44e646)
![Swampert](https://github.com/user-attachments/assets/615f0422-ea2c-43c2-98b4-03c9ea9e8da2)
![Tsareena](https://github.com/user-attachments/assets/f41bc506-61ab-4549-9cc5-37ab2b8cf1e6)
![Ursaluna](https://github.com/user-attachments/assets/53768412-60fb-4318-a554-fc71dd264050)
![Volcarona](https://github.com/user-attachments/assets/5573bbe0-3006-4175-aee6-71b644cb7378)
	
</details>

<details>
	<summary>Blur</summary>

![Blur](https://github.com/user-attachments/assets/18d4c412-cba2-4f0b-8046-972b4ea0b86d)

</details>

# Color Presets
You can create your own color preset using the following format in a snippet.
```
.preset-yourpresetname {
	--grotto-accent-h: ;
	--grotto-accent-s: ;
	--grotto-accent-l: ;
	--grotto-light-0: hsl();
	--grotto-light-1: hsl();
	--grotto-light-2: hsl();
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
#Note : The presets included in the theme are always subject to change. '

# The Plugin
The [Hidden Grotto Controls](https://github.com/HotAndCold245/Hidden-Grotto-Controls) plugin includes all the settings available in **Style Settings** as well as an easy way to cycle through the presets and toggle blur through ribbon commands. There's no need to use it if you don't need the shortcuts. 

# Feedback
If there are any problems with the theme, you can submit an issue on the repository.
