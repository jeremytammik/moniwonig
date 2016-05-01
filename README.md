# moniwonig

renovation plan for moni's new flat.

the todo list is stored and edited in markdown in [index.md](index.md).

it is converted to html in [index.html](index.html) using [markdown_py](https://pythonhosted.org/Markdown).

the result is published and displayed using gh-pages.

i originally tried rendering the md to html on the fly
using [showdown.js](https://github.com/showdownjs/showdown) as
suggested by theo armour in
his [explayrimental Showdown demo for Jeremy](https://github.com/theo-armour/explayrimental/tree/gh-pages/tammik/showdown).

unfortunately, it was not obious how to handle href links within the document using that approach, so i reverted to this less intelligent and more robust one instead.

in any case, i edit the web page directly in markdown and it is converted to html for rendering in the browser.
