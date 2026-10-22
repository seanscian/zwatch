# zwatch
watch for macOS implemented in zsh

Just drop this into a file in your personal directory and source it.

I didn’t like how `watch` builds on macOS couldn’t handle unicode/UTF-8, how MacPorts doesn’t understand macOS ncurses compatibility (no, you don’t actually need ncurses 6.6 installed in /opt/local for a lot of MacPorts to function), and how `watch` is blind to functions.

~~Could I have hacked on the watch binary?~~ Yeah.

~~Will I add `zcurses`?~~ Probably not.

Will I create a `man` page? You bet.

But this does what I need it to do right now, it might be useful to others, and I am going to keep expanding on it.

I’ve added some toggles for each of the short flags. `w` toggles line wrap, `t` toggles title bar, etc.

TO-DO: terminal width of multi-byte characters in right-to-left languages is improperly calculate in the title bar.
