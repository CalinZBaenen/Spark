- Added the *Cons* section to the README file's table of contents.  
- Gave Spark its (new) logo.

- Headings, group one to six, no longer have their font size changed by
   default.  
- The body no longer uses a flex layout by default.  
- Added `indented` value for `data-textstyle`.  
- Removed `data-hanging` and added the `hanging` adjective (of `indented`)
   for `data-textstyle`.  
- Removed `data-fullwidth` and `data-sticky`.  
- Removed the `iblock` and `inline` values for the `data-flow` attribute.  
- Added `data-cascade`, which allows you to apply any of same styles to all
   of an element's descendants — the styles to cascade are specified by
   using an attribute's name as a value.  
- Removed `data-pixelated-children` and `data-crisp-children` in favor of
   the behavior provided by `data-cascade`.  
- Changed the default style of `<hr>`s in `text/text.css`.  
- Added more support for the flex layout (using `data-flow="flex"`) in
   older browsers.