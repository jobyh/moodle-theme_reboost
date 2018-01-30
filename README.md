About this theme
================

This is a temporary theme, it was build based on the Boost theme. The aim of this project is to upgrade Boost to Bootstrap 4 Stable

How to use:
-----------

1. Install this theme in your Moodle '/themes' folder.

2. Enable theme in your theme selector


Contents:
---------

The SCSS folder contains the BS4 sass. Some sass has been commented out, the Moodle SASS PHP compiler does not support things that start with "@supports".. which is ironic :)

This project contains a Gruntfile.js and a package.json to enable compiling sass to scc. This reduces time for development and gives better error messages. Idealy I would like a better sass compiler in mdl but that is something else to worry about later.

Most of the original Moodle sass has been included. Only tiny fixes were made to make sure grunt can compile this.

Todo's
------

Write AMD modules based on the original Bootstrap JS. Then write a readme on how it was done. BS4 now includes Popper which is also included in the user tours. So it is already in core. It could simply be included in the theme again.

Search and find all uses of ".card" in Moodle. Think of something better or just improve the design.

Check all grids. This all uses Flexbox now and might break some mdl pages, especially when the original grid has addes MDL css

Fix dropdowns, use BS dropdowns instead of the ones triggered by MDL core JS.
