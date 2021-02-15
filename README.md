Technical documentation page, used to condense and compile notes.

# Things to add:

- JavaScript page
- Syntax highlighter for `<code>` blocks - [prism?](https://prismjs.com/#basic-usage)
  - Inline Color & Match braces
- Linkable keywords? 
- HTML/CSS page
- Markdown? [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Fonts
- Foundations-fundamentals.html notes 
- A function library?

## Tips + tricks section?

 - Select chunk of code, ctrl + k + c to comment it out
 - Ctrl + / line comment
 - Ctrl + shift + a block comment
 - Tag wrapping: select code, ctrl + shift + p, 'emmet: wrap', enter tag name
 - Code formatting: ctrl + shift + i
 - Multi-cursor selection - alt + shift + up/down, then can add/edit multiple lines as needed!
 - Markdown preview: ctrl + k, v
 - Emmet syntax: type 'nav>ul>li' and it will auto-tag that into the file...
 - Git info/commands?
   - e.g. git init, always forget to add before commit which causes problems
 - etc.

# Things to fix:

- ~~Scrolling L/R when window is ~50% - covers the menu area~~
  - Set the #main-doc to flex: 1 to be remainder of size
- ~~Menu is scuffed when minimal width - need to collapse menu?~~
  - Changed the media attributes for min-width and such; changed height of menu to be smaller, and set to sticky with z-index 1 to be on top at all times

