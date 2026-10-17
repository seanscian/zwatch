# zwatch
watch for macOS implemented in zsh

Just drop this into a file in your personal directory and source it.

I didn’t like how `watch` builds on macOS couldn’t handle unicode/UTF-8, how MacPorts doesn’t understand macOS ncurses compatibility (no, you don’t actually need ncurses 6.6 installed in /opt/local for a lot of MacPorts to function), and how `watch` is blind to functions.

Could I have hacked on the watch binary? Yeah.

Will I add `zcurses`? After that last commit, that’s next.

Will I create a `man` page? You bet.

But this does what I need it to do right now, it might be useful to others, and I am going to keep expanding on it.
