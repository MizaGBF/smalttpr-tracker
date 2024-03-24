# smalttpr-tracker

* Known Bugs
  * Doesn't keep inventory if you switch views
    * To counteract this, open one tab for each game **then** start modifying settings
    * Reloading either page will clear your inventory

This is an item tracker for LTTP: Randomizer. Use it at http://smalttpr.mymm1.com/tracker (hosted on my site, usually running a beta version) or https://miketrethewey.github.io/smalttpr-tracker/ (hosted here on Github, usually running a stable version)

This is a fork of the tracker at ```https://lttp-tracker.firebaseapp.com/``` and of Hyphen-ated's fork at https://github.com/hyphen-ated/lttp-tracker/

If you want to modify that version, you need to re-host it yourself on firebase, which is a big hassle. This version can easily be tweaked and changed locally. This meant taking out the networking features that let you do things like have a stream viewer run your tracker for you.

### About this repo

It has been modified to properly save the progress in the browser localstorage even if you close the window.  
You can access it [here](https://mizagbf.github.io/smalttpr-tracker/).  