### Version 001 (Mid October 2011)

Removed deprecated `coffee_folding` option, added `coffee_compile_vert`
variable, split out compiler, fixed indentation and syntax bugs, and added Haml
support and omnicompletion.

 - The coffee compiler is now a proper vim compiler that can be loaded with
   `:compiler coffee`.
 - The `coffee_compile_vert` variable can now be set to split the CoffeeCompile
   buffer vertically by default.
 - CoffeeScript is now highlighted inside the `:coffeescript` filter in Haml.
 - Omnicompletion (`:help compl-omni`) now uses JavaScript's dictionary to
   complete words.