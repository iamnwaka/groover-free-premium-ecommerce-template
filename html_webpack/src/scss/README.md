# Outside files
In `scss/` directory you could see 14 files or more.

#### App File
The app file (usually labelled `app.scss`) which is not begun with a `_`. This is our main file which contains whole styles for our layout.
##### Different color variations
All other files that are starting with `app.` prefixes are usually another variation of the same `app.scss` file for different color.

#### Vendor File
The vendor file (usually labelled `vendor.scss`) which is also not beginning with a `_`. This is our main vendor file which contains every dependency style that our layout needs.

#### Utility File
The Utility file (usually labelled `utility.scss`) contains all utility classes that are using this layout.

#### Config-Attacher File
The `config.attacher.scss` file contains configuration styles that are attached to our layout.

#### Header-Comment File
The header-comment file (usually labelled `header-comment.scss`) is just a SCSS file which contains only comment section. This comment section is just for `Table of contents` that helps us to navigate the compiled `CSS` file area.

#### Responsive File
The responsive file (usually labelled `_responsive.scss`) should contain all `media queries` styles that requires for our layout. Remember if a `component` has a `media query` style then `media query` style will be writing on its own `component` file. This file only contains responsive styles for just layout and nothing else.
File also starts with an underscore so basically this file will be import on the `app.scss` file.
