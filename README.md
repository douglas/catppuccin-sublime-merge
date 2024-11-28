<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://www.sublimetext.com">Sublime Merge</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/sublime-merge/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/sublime-merge?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/sublime-merge/issues"><img src="https://img.shields.io/github/issues/catppuccin/sublime-merge?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/sublime-merge/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/sublime-merge?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/68803793/203905911-e9569b4c-af9b-45ef-918d-f38015f1e0f0.png"/>
</p>

## Usage

### Installation

1. Navigate to the Sublime Merge Packages directory (Ex: `MacOS` : `~/Library/Application Support/Sublime\ Merge/Packages`)
2. Clone it! `git clone git@github.com:douglas/catppuccin-sublime-merge.git "Theme - Catppuccin"`
3. Update Preferences (Replace `Frappe` with the desired theme `Latte` `Macchiato` `Mocha`)

```json
{
    "theme": "Catppuccin Frappe.sublime-theme",
    "color_scheme": "Catppuccin Frappe.sublime-color-scheme",
}
```

## Development

### Local modifications
If you're unfamiliar with Sublime Text color scheme development, see ["Color Schemes" in the Sublime Text documentation](https://www.sublimetext.com/docs/color_schemes.html).

For local editing, you can invoke `UI: Customize Color Scheme` in the command palette to open a split-pane window with the current color scheme on the left and an override file on the right. Rules you add to your override file will be processed after the rules in the official color scheme.

If you have a specific piece of code you would like to re-color, you'll need to know what scopes are being applied to the token. (Applying scopes is done by the syntax, not the color scheme.) Position your caret over the token, and use <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> (or **Tools** > **Developer** > **Show Scope Name**). Then add a rule in your color scheme override to apply a color to this token.

### Contributing modifications
1. Clone this repository and open it
2. Apply your changes to `sublime-color-scheme.tera`
3. Re-build the 4 flavors with `whiskers sublime-color-scheme.tera`
  4. To install Whiskers, the Catppuccin helper tool, see https://github.com/catppuccin/whiskers
4. Open a Pull Request!

## 💝 Thanks to

- [douglas](https://github.com/douglas)

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
