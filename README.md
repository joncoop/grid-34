# Odin: A CSS Framework

## About

Odin is a simple, easy-to-understand grid framework that can be used to quickly create complex, fully-responsive layouts. View the documentation to [get started](http://joncoop.github.io/odin/).

## History

- 0.1.0 - Created basic grid structure with rows and columns. Added containers. (2016-11-04)
- 0.2.0 - Added a bunch of positioning helper classes, row reverse. Added classes to show/hide based on viewport. Added class to make img, iframe, and video elements responsive. (2016-11-05)
- 0.3.0 - Added ability to change gutter sizes. Added classes to float and center images. Added text alignment classes. img, iframes, video are responsive by default now. (2016-11-06)
- 0.4.0 - Added rounded and circle image classes. (2016-11-12)
- 0.5.0 - Added basic table styling, responsive table classes, and even/odd row shading helper classes. (2016-11-12)
- 0.6.0 - Added form styling. (2016-11-27)
- 0.7.0 - Added responsive navigation elements. (2016-12-23)
- 0.7.1 - Cleaned up color palette, grid spacing, and typography, simplified resets. (2017-01-23)
- 0.8.0 - Added typography styling, navbar markup simplified, bug fixes. (2017-01-28)
- 0.9.0 - Added button styling, forms use new buttons, minor color and typography tweaks. (2017-01-29)
- 0.9.1 - Responsive utilities rewritten to hide on size-and-up and size-and-down. Show classes removed. (2017-01-29)
- 0.9.2 - Evenly spaced navbar links are working. Not super pleased with the implementation, still incompatible with responsive features. (2017-01-29)
- 0.9.3 - Fixed z-index bug with slideout menus. (2017-01-30)
- 0.9.4 - Fixed another z-index bug with slideout menus. Fix Firefox/IE slideout navbar layout quirks. (2017-01-30)
- 0.9.5 - Bug fixes, CSS reorganization, and lots of documentation comments added to CSS. (2017-01-30)
- 0.10.0 - Added call-outs. (2017-01-31)
- 0.10.1 - Blockquote bug fixes. (2017-01-31)
- 0.10.2 - Added unstyled list class. (2017-02-01)

## To do

### for v1.0
- Fix row-reverse (possible just update documentation to show better usage)
- There's something that just doesn't feel right about the grid breakpoint/container sizing and naming relationship. Gotta do some math and think this through.
- Possibly simplify navbar markup. Give evenly spaced navbar compatible with responsive features.
- General code cleanup, clean up color palette, minor styling tweaks, bug fixes.
- Remove JQuery dependency for slideout menu.
- Add containers that snap to widths according to viewport.

### for 1.0+
- Add 'sticky' features for header and footer elements.
- Create row-10 class and corresponding col classes to have rows based on 10ths. (Or take advantage of flex for autosizing column classes.)

## more ideas (not to include in css/js, just write instructions)
- Icon fonts
- Image carousels (owl-carousel)
- Add default code styling, syntax highlighting

## for fun
- Make the docs much prettier
- Work on theme template
