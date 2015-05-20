# emacsperator
A .vimperatorrc file that makes vimperator act like emacs

Based on [this](https://gist.github.com/avendael/7028513). edited to work with versions of vimperator past 3.0, by removing references to guioptions and showtabline, and also fixing various other stuff.

remaining issues:
 * when in hint mode, C-g opens a find dialog instead of actually exiting
 * firefox interprets M-v as 'let's open the view menu because i'm an idiot' instead of jump scrolling up. this should be fixed by setting ui.key.menuAccessKey in about:config to 0, but it isn't. This appears to be a bug in firefox (using firefox 38.0 on ubuntu 14.04)
 * vimperator keybindings won't work after i have clicked 'pause' on a youtube video. i have to click outside the video to get them to work again.
 * problems in text editing mode, for instance C-SPACE doesn't work, and can only paste using C-v, not C-y.

note: there may also be issues with various keybindings here that i simply didn't feel like using and therefore didn't bother to test. ymmv.
