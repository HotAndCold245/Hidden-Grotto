# Hidden-Grotto-Theme
A theme for the Obsidian app
# Introduction
This theme takes inspiration from Pokemon typing and design. There is a separate plugin called the **Hidden Grotto Theming Tool** which allows you to choose a *primary* and *secondary* color type, much like how Pokemon can have a combination of 2 types from a selection of 18. Each type is associated with a different color and affects different parts of the theme. Ignoring the plugin, the theme's base color palette is taken from the Pokemon [[Clobbopus]]. 
%% Image of the theme goes here %%**
![[Screenshot 2025-10-06 165639.png]]


## Modified Features
###### Mobile Toolbar
The mobile toolbar no longer scrolls horizontally. It will now create vertical rows when there are more tools than a single row can hold. By default, up to 2 rows can be visible before needing to scroll. A css snippet can be used to adjust the number of visible rows. An example of what you need to add is:
```css
.mobile-toolbar {
    height: calc(36px + ((var(--grotto-toolbar-rows) - 1) * 28px));
}
```
Here, `--grotto-toolbar-rows` is the number of rows you want to keep visible. The plugin also allows to easily adjust the number of rows as well as the background accent of the toolbar. 
%% Image of the mobile toolbar goes here %%
![[Screenshot_2025-10-06-17-00-18-32_51606159b24eff83e24a54116878fe3e.jpg]]

###### Mobile View Actions
The view actions - extra options and reading view buttons at the top right of the screen have been moved to the bottom for easy reach. The reading view button is hidden behind the command palette button but is visible when the on-screen keyboard is active while typing. The editable file path is also hidden to increase space. 

###### Calendar Plugin Support
Calendar plugin is styled. 
%% Image of the calendar plugin %%
![[Screenshot 2025-10-06 170655.png]]


# The Plugin
%% Link to the plugin goes here %%
Details about the plugin are discussed here as they are more relevant in the context of the theme. The theme can be used without the plugin but will lack customizability beyond what snippets can provide. The primary purpose of the plugin is to switch color types and access presets. 
![[Screenshot 2025-10-07 131913.png]]

## Color Typing
The plugin allows the user to select a primary and secondary color for the theme. This is similar to how Pokemon can have upto 2 types. The primary and secondary colors will affect different parts of the theme where primary will affect the major portions such as text-color, container-backgrounds, etc. while secondary will affect subtexts, icon colors, bold/italic color, etc. Any combination of the 18 available types will work. 
%% Show examples of different color combinations here %%

## Presets
The plugin also allows the use of presets. These presets can be defined in a snippet using the identifier `body.preset-` . For example, `body.preset-clobbopus` will be used if **Clobbopus** is typed into the field. You can set your own preset using the available variables if using the Hidden Grotto Theme or just the standard obsidian variable if using the plugin on its own. This feature works standalone and allows you to save your own presets in snippets to swap between. Available presets are also displayed in the settings tab. They update automatically according to enabled snippets and themes using the identifier. 

Note: The preset overrides the primary and secondary color options but swapping those colors will override the preset. 

## Other Settings
There are other settings pertaining to text and table customization as well as some mobile specific options. 


## Ribbon Icon/Palette Command
There are two commands associated with the plugin to cycle through the primary and secondary color types. The dragon type icon is for the primary color and the flying type icon is for the secondary color. 
![[Screenshot 2025-10-07 134607.png]]

# Conclusion
I'm probably missing some minor details. I will add them later if they exist. The font used alongside the theme is called Quicksand. 

