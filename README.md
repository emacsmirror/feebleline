# feebleline
For hardline Luddite editing!

Feebleline removes the modeline and replaces it with a slimmer proxy
version, which displays some basic information in the echo area
instead.  This information is only displayed if the echo area is not used
for anything else (but if you switch frame/window, it will replace whatever
message is currently displayed).

NOTE:
feebleline.el will look considerably better with the following
settings:

    (window-divider-mode t)
    (setq window-divider-default-bottom-width 1)
    (setq window-divider-default-places (quote bottom-only))

But this mode does not work for all EMACS versions and may not work with
terminal EMACS (but I haven't checked).  If you're on GUI EMACS and your
version supports it, just place the following in your init file:

    (feebleline-default-settings)

Otherwise, do (feebleline-mode t) instead, but be warned that I'm not sure
if it will look good.

Note: Code graciously improved by *Kungsgeten*. I tweaked it a little bit more
to make it easier to customize colors etc and defined some default faces. If
anyone has any ideas for nicer default faces, let me know and I'll consider
them!

New screenshot :
![Alt text](scrot2.png?raw=true "Screenshot2")

How it looks when the file has been modified:
![Alt text](scrot3.png?raw=true "Screenshot3")
