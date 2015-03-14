# tsuntsun - A build manager thing

Okay, so what the heck is this? If you're asking that; you're probably not
the intended target. Sorry.

On the offchance you've done LFS (linux from scratch) before, chances are
you probably have a personal shell script suite much like mine.

That said, mine is tsundere. Named for the fact that half of the configs
I do can't decide whether to explode or not. Seems appropriate, no?

This script package will never ever ever ever do the following:

 * dependency resolution
 * systemd

I might add package flag detection from configure --help, and add global
supported flags. I will not do dependency detection.

Why? Because preferences. Inevitably, dragging in other things is only
okay if you know what a user wants. I am me. You are you. You might
want to run GNOME3 on uselessd. I might want to apply a patchset to
remove every reference to systemd.

Or, you might want pulseaudio patches on wine. I might not want those,
but I might want staging patches.

The issue; dep resolving is crap. It always has been.
