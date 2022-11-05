# Gnome Packages (My Customized Packages Archlinux)

![My Image](/images/gnome-packages.png)

## Gnome-Shell_n7n: 

 - This package disables Overview Mode entirely.
 - It also adds the Performance-related MRs (merge requests) from gitlab.
 
This build of GS simplies and gives a more conventional Desktop experience. However, due to GS's Overview Mode being 
disabled; any related/dependent features will not work. For example, I replace the GS overview search function with Albert,
as Albert is less distracting anyway. (much more akin to Spotlight on MacOS, which i like better).

Overview Mode is a bit racy with multi-touch gestures/input; it won't always release dragged windows going into Overview 
Mode and sometimes freezes. Additionally, Gnome is much faster without Overview mode, with less hiccups under significant load...

## Mutter_n7n: 

 - This package package adds performance related MRs.
 - This package adds the mutter-rounded/blur patches.
 
This build of mutter pulls in the performance and mutter-rounded patches. Later I will adjust the defaults to match 
my own tastes / configuration.

NOTE: as of Gnome-43, this mutter package only supports x11. full stop.

## Gnome-Terminal-Lefty:

 - This package adds transparency to the terminal
 - This package contains a patch to move the scrollbar to the left-side (for left-handed Stylus/Tablet users. 

no support provided, as these are for my own personal use.
