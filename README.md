# pdf-pagelabels

A small Python command line tool to add page labels to PDFs

Here's the help message:

```plain
usage: pdf-pagelabels input output page_range [OPTIONS] [page_range [OPTIONS]...]

Add page labels to a PDF file

positional arguments:
  input                 Input PDF file
  output                Output PDF file
  page_range [OPTIONS]  Page range and label specifications

options:
  -h, --help            show this help message and exit
  -s S, --style S       Page label style, one of D, R, r, A, or a
  -p P, --prefix P      Page label prefix
  -t NUM, --start NUM   Starting number for page labels
```
