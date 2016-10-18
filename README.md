# Prot One dark UI

**EXPERIMENTAL. DO NOT USE IT WITHOUT ANY ONE OF [MY SYNTAX THEMES](https://atom.io/users/protesilaos/themes).**

This theme is a fork of the otherwise excellent [One Dark UI](https://github.com/atom/one-dark-ui). I have created it to serve the very basic need of a UI accompaniment to my syntax themes.

## The 'why'

Each item in my [Prot16 collection](http://www.protesilaos.com/schemes) consists of a coherent sixteen-colour palette. There are eight accent plus two sets of base values.

- The former are variations of red, orange, yellow, green, cyan, blue, violet, and magenta. They are common to either the light or dark version of a theme.
- The latter govern the background and foreground colours that define the theme's instantiation as light or dark.

The base sets are mutually exclusive even though they still belong to the same palette. This means that every syntax theme actually uses a maximum of twelve out of the sixteen colours. The other four are simply ignored.

What this UI theme is meant to do is apply those four values to the interface.

- With my light themes it will create a rather high contrast between the editor and the other components, such as the side bar, the tab bar, and the status bar. Those will inherit the dark base.
- With dark themes though, the difference will be far more subtle. A gradient in fact, with the components being darker than the editor.

## The 'when'

This package will be published once I have tested it extensively on all of my themes. I also need to resolve errors or conflicts that emerge when using it in combination with a syntax theme other than my own. Personally I already use this UI theme as a local package. However it would be highly irresponsible to publish somethin in the official repositories and is well known to break things when sued with every syntax theme that was not designed by me.

If you are using my syntax themes and would like to try this out, clone this repo and then type the following commands in your terminal:

```shell
cd ~/prot-one-dark-ui
apm link
```

This creates a symbolic link with the Atom editor so that the theme can be selected from the settings menu.

I repeat: **_Prot One Dark UI_ is an experimental project. Do not use it without one of my syntax themes.**
