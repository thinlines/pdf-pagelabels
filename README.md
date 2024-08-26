# pdf-pagelabels

A small Python command line tool to add page labels to PDFs

Here's the help message:

```python
usage: pdf-pagelabels input output page_range [OPTIONS] [page_range [OPTIONS]...]

Add page labels to a PDF file

positional arguments:
  input                 Input PDF file
  output                Output PDF file
  page_range [OPTIONS]  Page range and label specifications

options:
  -h, --help            show this help message and exit
  -s PAGE_RANGE, --style PAGE_RANGE
                        Page label style, one of D, R, r, A, or a
  -p PAGE_RANGE, --prefix PAGE_RANGE
                        Page label prefix
  -t PAGE_RANGE, --start PAGE_RANGE
                        Starting number for page labels
```
