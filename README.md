# win32-framebuffer-patterns

This program contains rapidly blinking lights and scrolling patterns that can be disorienting for some users. Please use with caution and do not state at the screen for extended periods of time.

A small rendering experiment that constructs a minimal framebuffer which stores pixels directly into RAM and then blits them to the screen all at once. Patterns are programmatically generated through manipulating each color byte every frame in order to give the appearance of animation.

Pattern functions are duplicated with only minor changes for each of them so that anyone interested in taking a look at the code could quickly see how each pattern was generated without diving into complex macro setups or other solutions for the sole purpose preventing code duplication.

Tested on Windows 11 64bit machines but this should also work on a 32bit Windows system as well.

## Controls

[Numbers 1-5] Changes the active pattern

[Arrows] Changes the horizontal and vertical scrolling speeds.

[Space] Pauses scrolling and freezes the pattern.

[R] Resets scrolling speeds back to default.

[F11] Toggles exclusive fullscreen mode.
