# linux-tools
Linux utility scripts


## Tools
* [g-screenshot-ocr](##g-screenshot-ocr)


## G Screnshot Ocr

This script use [gnome-screenshot](https://gitlab.gnome.org/GNOME/gnome-screenshot) and [tesseract-ocr](https://github.com/tesseract-ocr/tesseract) 
to make screenshot and read text from this. To use this tool:

```bash
$ g-screenshot-ocr <lang>

```

If You want use other lang than `eng`, that You need to install `tesseract-ocr-<lang>` packages wher `<lang>` is language that You need;  
  
Example: 
```bash
$ sudo apt install tesseract-ocr-pol
```
