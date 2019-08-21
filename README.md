# Mojave Alfred Accented Themes
Collection of Dark & Light Accented Alfred Themes tailored with care for macOS Mojave & Alfred Powerpack users.  
You can have any color! Well, as long as it's *not* Black 🎩


## Releases

- 1.2.1 : Fixed the ```theme install``` command. *August 2019*
- 1.2.0 : New ```theme install``` command to easily download the 16 themes at once. *July 2019*
- 1.1.1 : Alfred 4 compatibility. *June 2019*
- 1.0.0 : Initial release. *October 2018*

## Installation

[Download the latest workflow](https://github.com/AlexMartinFR/mojave-alfred-accented-themes/raw/master/workflows/Mojave%20Themes%20Switcher.alfredworkflow), then use the ```theme install``` command to grab the 16 themes at once!
I personnaly rock the Light Purple one most of the time, and disabled the Hat Logo in Alfred's Preferences.

*If you want to clean your Alfred themes folder, here are some terminal shortcuts to open the most common Alfred preferences' locations:*

- ```open ~/Library/Application\ Support/Alfred/Alfred.alfredpreferences/themes```
- ```open ~/Library/Application\ Support/Alfred\ 3/Alfred.alfredpreferences/themes```
- ```open ~/Library/Application\ Support/Alfred\ 2/Alfred.alfredpreferences/themes```

## Theme Switcher

The workflow designed for this theme collection allows you to select your Alfred's theme accent color and switch between Dark & Light modes. Here are the main commands :
- ```theme``` : toggles between Dark & Light Themes on **both macOS and Alfred**. 
- ```theme color``` : toggles between the accent color of your choice variant of this set of themes (replace *color* with either *Blue*, *Purple*, *Pink*, *Red*, *Orange*, *Yellow*, *Green*, *Gray*).

<p align="center">
  <img src="previews/mojave-theme-switcher.gif" width="600" alt="Mojave Theme Switcher Workflow" />
</p>



## Known limitations

- To preserve your actual accent color when toggling between Dark and Light modes, I use the themes' background color as an identifier for a specific accent. Which means if you modify the colors of the themes, or try to adapt it for another set of themes, you'll have to adapt the "accentColorLookup" table.
- There is currently no macOS API that I know of which features a way to change the system UI's accent color. When Apple adds it, I'll add the feature to toggle everything from this workflow at once, which will make it a breeze to swap colors system wide in one command!


## Previews


<p align="center">
  <img src="previews/mojave-light-blue.png" width="596" alt="Mojave Light - Blue" />
</p>

<p align="center">
  <img src="previews/mojave-light-purple.png" width="596" alt="Mojave Light - Purple" />
</p>

<p align="center">
  <img src="previews/mojave-light-pink.png" width="596" alt="Mojave Light - Pink" />
</p>

<p align="center">
  <img src="previews/mojave-light-red.png" width="596" alt="Mojave Light - Red" />
</p>

<p align="center">
  <img src="previews/mojave-light-orange.png" width="596" alt="Mojave Light - Orange" />
</p>

<p align="center">
  <img src="previews/mojave-light-yellow.png" width="596" alt="Mojave Light - Yellow" />
</p>

<p align="center">
  <img src="previews/mojave-light-green.png" width="596" alt="Mojave Light - Green" />
</p>

<p align="center">
  <img src="previews/mojave-light-gray.png" width="596" alt="Mojave Light - Gray" />
</p>




<p align="center">
  <img src="previews/mojave-dark-blue.png" width="596" alt="Mojave Dark - Blue" />
</p>

<p align="center">
  <img src="previews/mojave-dark-purple.png" width="596" alt="Mojave Dark - Purple" />
</p>

<p align="center">
  <img src="previews/mojave-dark-pink.png" width="596" alt="Mojave Dark - Pink" />
</p>

<p align="center">
  <img src="previews/mojave-dark-red.png" width="596" alt="Mojave Dark - Red" />
</p>

<p align="center">
  <img src="previews/mojave-dark-orange.png" width="596" alt="Mojave Dark - Orange" />
</p>

<p align="center">
  <img src="previews/mojave-dark-yellow.png" width="596" alt="Mojave Dark - Yellow" />
</p>

<p align="center">
  <img src="previews/mojave-dark-green.png" width="596" alt="Mojave Dark - Green" />
</p>

<p align="center">
  <img src="previews/mojave-dark-gray.png" width="596" alt="Mojave Dark - Gray" />
</p>



## Inspiration and thanks

- Thanks to <a href="https://github.com/dvlden/alfred-themes">dvldev for his stylish themes</a>,
which inspired me to further embrace macOS Mojave's Accent Colors 🙏
- Thanks also to <a href="https://github.com/mermaid/mojave-darkmode-toggle">mermaid</a> for the Theme Switcher workflow inspiration 👌
- Thanks to Mike Barker's suggested fixes, which led to a very quick Alfred 4 compatibility update 👍
