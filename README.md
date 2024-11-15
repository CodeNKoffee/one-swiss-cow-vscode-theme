# One Swiss Cow - VSCode Theme

One Swiss Cow is a delightful VSCode theme inspired by the cows of the Swiss Alps. This theme wraps you in a whimsical tale straight from the heart of a mountain farmer, delivering a coding experience as refreshing as an alpine breeze. The colors in this theme will moo-ve you, setting the perfect atmosphere for any project!

## Features

	•	Unique Color Palette: A Swiss Alps-inspired color scheme, designed to give you a fresh, calming, and focused environment while coding.
	•	Dark Mode: This theme is optimized for the vs-dark UI theme, providing a comfortable and easy-on-the-eyes experience during long coding sessions.
	•	Fresh and Whimsical: The playful colors bring a bit of fun to your workspace, drawing inspiration from the rural charm of mountain life.

## Installation

	1.	Open VSCode.
	2.	Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
	3.	Search for One Swiss Cow.
	4.	Click Install.

Alternatively, you can clone this repository and install the theme manually:
	1.	Clone this repository:

git clone https://github.com/your-username/one-swiss-cow.git


	2.	Open the folder in VSCode.
	3.	Press F5 to open a new VSCode window with the theme enabled.

## Usage

Once installed, you can activate the theme by following these steps:
	1.	Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) to open the Command Palette.
	2.	Type and select Preferences: Color Theme.
	3.	Choose One Swiss Cow from the list.

## Configuration

This theme is designed to work seamlessly with the vs-dark UI theme, but you can adjust your workspace settings to match your preferences. Here are some customizations you can add to your settings.json file:

"workbench.colorTheme": "One Swiss Cow",
"editor.fontFamily": "Fira Code, monospace",
"editor.fontSize": 14,
"editor.lineHeight": 22

## Package Information

{
  "name": "one-swiss-cow",
  "displayName": "One Swiss Cow",
  "description": "An inspired color palette crafted from the cows of the Swiss Alps, wrapped in a whimsical tale straight from the heart of a mountain farmer. Step into a coding experience that feels as refreshing as an alpine breeze, with colors that moo-ve you.",
  "version": "0.0.1",
  "engines": {
    "vscode": "^1.95.0"
  },
  "categories": [
    "Themes"
  ],
  "contributes": {
    "themes": [
      {
        "label": "One Swiss Cow",
        "uiTheme": "vs-dark",
        "path": "./themes/One Swiss Cow-color-theme.json"
      }
    ]
  }
}

## Contributing

Feel free to fork and submit pull requests! Whether it’s a bug fix, new feature, or just a simple suggestion, contributions are always welcome.

## License

This theme is licensed under the MIT License. See LICENSE for more details.