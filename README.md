This is a project of good practice document for academia.

To build the book, use one of these commands:
```
bookdown::render_book('index.Rmd', 'html_document')
bookdown::render_book('index.Rmd', 'bookdown::gitbook') # most interactive format
bookdown::render_book('index.Rmd', 'bookdown::pdf_book') # you need LaTeX
```
The bookdown documentation by Yihui Xie is very complete:
* For rMarkdown documentation, see here: https://bookdown.org/yihui/bookdown/markdown-syntax.html
* rMarkdown cheatsheet: https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf
* For even more complete documentation of markdown see http://pandoc.org/

The present project is based on: a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at https://bookdown.org/yihui/bookdown/ for how to compile this example into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

