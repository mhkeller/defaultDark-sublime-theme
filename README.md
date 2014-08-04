DefaultDark Sublime Theme
===

Like your default Sublime theme but with a dark sidebar.

## Installation

### With Git

`cd` into your Sublime Text 2 `Packages` directory. Usually

````
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
````

You can open this folder and check its path by navigating the Sublime toolbar: `Sublime Text 2 -> Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository with:

````
git clone https://github.com/mhkeller/defaultDark-sublime-theme.git "Theme - DefaultDark"
`````

### With manual download

* Download the files using the GitHub .zip download option
* Unzip the files
* Copy the folder to your Sublime Text 2 `Packages` directory

## Activate the color theme

Go to `Sublime Text 2 -> Preferences -> Settings - User`.

Add this line, or change your existing line to include this

````
"theme": "DefaultDark.sublime-theme"

````

Don't forget to add a comma after `"ignored packages"` entry. Your full file should look something like this

````
{
	"color_scheme": "Packages/User/Color Highlighter/Monokai.tmTheme",
	"font_size": 12.0,
	"ignored_packages":
	[
		"Vintage"
	],
	"theme": "DefaultDark.sublime-theme"
}

````