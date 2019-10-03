# Shades-of-pastel

Shades-of-pastel is a dark syntax color scheme for several editors. By using pastel colors on dark background similar to pastel chalks on a blackboard the Shades-of-pastel scheme provides balanced and eye-friendly contrasts.

## Table of Contents

- [Installation](#installation)
  - [Download](#download)
  - [Shades-of-pastel in Vim, GVim](#vim-gvim)
  - [Shades-of-pastel in Sublime Text](#sublime-text)
  - [Shades-of-pastel in Gedit, Pluma, Xed, Mousepad](#gedit-pluma-xed-mousepad)
- [License](#license)

## Installation

### Download

You can download and extract the [ZIP package](https://github.com/WernerFP/Shades-of-pastel/archive/master.zip) from GitHub or clone the GitHub repository:
```
git clone https://github.com/WernerFP/Shades-of-pastel.git
```

The following syntax highlighting files are included:
* `shades-of-pastel.vim` for Vim or GVim
* `Shades-of-pastel.tmTheme` for Sublime Text
* `shades-of-pastel.xml` for *GtkSourceView* editors

---

### Vim, GVim

To install Shades-of-pastel for Vim change to directory `Shades-of-pastel/Shades-of-pastel_Vim`. Copy the file `shades-of-pastel.vim` into your Vim profile folder - the Linux way:</p>

```
mkdir -p $HOME/.vim/colors
cp shades-of-pastel.vim $HOME/.vim/colors/
```
Turn on syntax highlighting (`syntax on`) in your configuration file (`~/.vimrc`) and append the line `colorscheme shades-of-pastel` if you want to use the Shades-of-Pastel scheme by default.

#### • Shades-of-pastel in Vim:

<p align="center">
<img src="https://user-images.githubusercontent.com/40271168/65055381-5b6d5580-d96f-11e9-87f4-c359500d53df.jpg" width="872px" height="474px"></img></br><i>Vim: Bash sample</i>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/40271168/65051828-ef3c2300-d969-11e9-9494-32c6940f7c83.jpg" width="872px" height="474px"></img></br><i>Vim: Ruby sample</i>
</p>

---

### Sublime Text

To install the scheme for Sublime-Text change to directory `Shades-of-pastel/Shades-of-pastel_Sublime-Text`. Copy the contained file `Shades-of-pastel.tmTheme` to a folder in your Sublime Packages directory - the Linux method:

```
mkdir -p $HOME/.config/sublime-text-3/Packages/Shades-of-pastel
cp Shades-of-pastel.tmTheme $HOME/.config/sublime-text-3/Packages/Shades-of-pastel/
```
To activate the color scheme in the sublime text you can use the menu item *Preferences &#8594; Color Scheme &#8594; Shades-of-pastel*.

#### • Shades-of-pastel in Sublime Text:

<p align="center">
<img src="https://user-images.githubusercontent.com/40271168/65053232-2820cb80-d95b-11e9-99db-437583b41862.jpg" width="872px" height="559px"></img></br><i>Sublime Text: C sample</i>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/40271168/65053263-340c8d80-d95b-11e9-9636-4abd46231e5e.jpg" width="872px" height="527px"></img></br><i>Sublime Text: HTML sample</i>
</p>

---

### Gedit, Pluma, Xed, Mousepad

Shades-of-pastel can be used by editors with syntax highlighting based on *GtkSourceView 3* or *GtkSourceView 4*. To install the syntax color scheme in Linux change to directory `Shades-of-gray/Shades-of-pastel_GtkSourceView`. Copy the contained file `shades-of-pastel.xml` into the following user directories:

```
mkdir -p $HOME/.local/share/gtksourceview-3.0/styles
cp shades-of-pastel.xml $HOME/.local/share/gtksourceview-3.0/styles/

mkdir -p $HOME/.local/share/gtksourceview-4/stylesColor Scheme
cp shades-of-pastel.xml $HOME/.local/share/gtksourceview-4/styles/
```
Shades-of-pastel is now available in the preferences of your editor.

#### • Shades-of-pastel in Gedit:

<p align="center">
<img src="https://user-images.githubusercontent.com/40271168/65053464-83eb5480-d95b-11e9-9fba-212053fed11b.jpg" width="872px" height="331px"></img></br><i>Gedit: Python sample</i>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/40271168/65053489-8e0d5300-d95b-11e9-8f6f-abc8e3e3db2a.jpg" width="872px" height="401px"></img></br><i>Gedit: CSS sample</i>
</p>

---

## License

GNU General Public License v3.0
