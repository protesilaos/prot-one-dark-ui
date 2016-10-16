# Prot One dark UI

**EXPERIMENTAL. DO NOT USE IT WITHOUT ANY ONE OF [MY SYNTAX THEMES](https://atom.io/users/protesilaos/themes).**

This theme is a fork of the otherwise excellent [One Dark UI](https://github.com/atom/one-dark-ui).  I have created it to serve the very basic need of a UI accompaniment to my syntax themes.

Each one of my colour schemes consists of a coherent sixteen-value palette. There are eight accent plus two sets of base values. The bases govern the background and foreground colours, which makes them mutually exclusive, even though they still belong to the same 'family' as it were. This means that every syntax theme actually uses twelve out of the sixteen colours. The other four are simply ignored.

What this UI theme is meant to do is apply those four values to the interface. With my light themes it will create a rather high contrast between the editor and the other components, such as the side bar, the tab bar, and the status bar. Those will inherit the dark base. With dark themes, the difference will still be visible, with the components being darker than the editor, though far more subtle.

This package will be published once I have tested it extensively on all of my themes. I also need to resolve errors or conflicts that emerge when using it in combination with a syntax theme other than my own.

If you are using my syntax themes and want to try this out, clone the repo and then type:

```shell
cd ~/prot-one-dark-ui
apm link
```

This creates a symbolic link with the Atom editor so that the theme can be selected from the settings menu. I repeat, **this is an experimental project**. Proceed at your own risk.
