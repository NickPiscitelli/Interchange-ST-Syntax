Interchange-ST-Syntax
=====================

Interchange E-commerce Sublime Text 2 Syntax Highlight

To install this package, simply copy the 'Interchange/' Folder 
to your Sublime Text 2 Packages directory. Once copied, restart 
Sublime and Interchange will be an available syntax mode.

Known Limitations:
No interpolation for IC tags in JS strings, CSS selectors, perl quote operators (e.g qq|)
JS hash element access gets identified as an IC tag.
Only calc,perl,set and tmp tags check for interpolation.

Expected Additions:
Add matching tag support.
Add folding support.
Restructure scope groups for improved formatting conventions.
Build common IC snippets.