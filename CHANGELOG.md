# Change Log

## 0.0.31
- Fix highlighting for `loop` keyword.

## 0.0.30
- Highlight `extern` as a storage modifier keyword.

## 0.0.29
- Highlight return values as variables.
- Highlight single letter variables & functions.
- Highlight custom types in variable declarations.
- Add meta match for `if let` statements.

## 0.0.28
- Defined `*` as *glob* operator.
- Defined `?` as *error-propagation* operator.

## 0.0.27
- Last tweak to variable highlighting for the time being.

## 0.0.26
- Reference highlighting looks to be working.

## 0.0.25
- Reference highlighting still needs some work.

## 0.0.24
- More improvement to struct highlighting.
- Highlight references as variables.

## 0.0.23
- (*hopefully*) Better highlighting for structs.

## 0.0.22
- Fixed pattern from 0.0.21.

## 0.0.21
- Don't require spaces between variables & equals.
- Highlight types in method (`impl`) blocks.

## 0.0.20
- Highlight lifetimes.

## 0.0.19
- Highlight variables in variable declarations.
- Highlight `T` & `U` as *entity.name.type.generic.rust*.

## 0.0.18
- Highlight type names in method statements.

## 0.0.17
- Fixed highlighting for method keyword with generic type params.
  - (ex: `impl<T> ...`)
- Highlight single letter function names.

## 0.0.16
- Fixed an issue where module names with numbers wern't being highlighted.
- Added additional variable highlighting.
- *Ensured* correct highlighting for function names with type params.

## 0.0.15
- Testing limited markdown support in doc comments (bold, italic, code strings, headings, and links).

## 0.0.14
- Highlight functions names that include (*but don't begin with*) numbers.

## 0.0.13
- Improved highlighting for fmt strings (final time, should be solid now).

## 0.0.12
- Improved highlighting for fmt strings (again).
- Highlight module names with underscores.

## 0.0.11
- Added type highlight to `HashMap`.
- Testing new variable highlighting.

## 0.0.10
- Highlight crate names in `extern crate ...`.
- Highlight variable in maps (`|x|`).

## 0.0.9
- Added version badge to readme.
- Improved highlighting for fmt strings (`"{}"`).
- Further improved highlighting for type params.

## 0.0.8
- Updated icon.
- Improved highlighting for type params.

## 0.0.7
- Fixed issue where `.` wasn't highlighted when preceded by a paren.
- Added items to todo.txt.

## 0.0.6
- Added highlighting for module names.
- Defined `:`  as type separator.
- Defined `.`  as *member-access* operator.
- Defined `..`  as *range* operator.
- Defined `_`  as *ignored* keyword.
- Defined `{` & `}` as *curly*.
- Defined `(` & `)` as *paren*.
- DEPRECATED:
  - `string.quoted.single.rust`

## 0.0.5
- Fixed an issue with comments.
- Defined `,` as `punctuation.comma`.
- Defined `;` as `punctuation.terminaor`.
- Defined `::`  as *path* operator.
- Defined `=>` as *match* operator.
- Defined `->` as *return-type* operator.

## 0.0.4
- Initial functionality.

## 0.0.3
- Updated readme.

## 0.0.2
- Marked as unstable.

## 0.0.1
- Init.
