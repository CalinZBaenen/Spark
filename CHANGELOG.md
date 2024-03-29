- Changed the wording and capitalization of line 35 of the README-file.  
- Renamed `test_table.html` to `table.html`.  
- Made the formatting of line-breaks consistent in the markdown files.  
- Reduced the amount of characters in
   [`table.html`](.examples/table.html)'s example using Mario from
   9375 to 4375.

- Deprecated `[data-centered]` (with no value).  
- Added `cross`, `both`, and `main` values for `[data-centered]`.  
- Added `[data-centered-children]` (for larger flex containers) with
   identical values to `]data-centered]`.  
- Added an `iblock` and `inline` value for `[data-flow]`, the latter of
   which can be combined with the `flex` and `grid` values of the same
   property.  
- Some values (like `inline` with `flex` and `grid`, or `dense` with `col`)
   act as adjectives, meaning they can combine with other values, nouns, to
   modify the behavior of the noun - such as `flex`, used to akes an
   element a flex-container, and `inline`, used to make elements inline,
   which combine to make elements an inline flex-container.  
- Adjectives are now moved before nouns in the CSS.  
- `[data-cutout]` can now be applied to `<tr>`s.