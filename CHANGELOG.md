- Updated the `text.html` example.  
- Added an example, `layout.html`, that shows off the layout features.  
- Added `font-family:sans-serif` in `examples/.assets/site_specific.css`.  
- Capitalized the "US" in "`en-us`" in the example files.

- `<code>` now acts as though it had `data-textstyle="code"` applied.  
- Moved the default styling for `<hr>`s from `text/text.css` to
   `layout/std.css`.  
- Added `@charset "UTF-8"` to the top of the CSS files that were
   missing it.  
- Added the `wrap` and `r-wrap` values for `data-flow`, which adds a way to
   make flex-containers wrap normally or in reverse.  
- Added the `inline` and `block` values for `data-flow`, which can be
   combined.  
- Added the `char` value for `data-padding`, which gives elements the
   padding of (about) one character.