# Astralinux file parser
This parser prints giant repo tree from dl.astralinux.ru/astra/ and calculates its size. The `size.py` makes size calculation and `main.py` parses and downloads (not yet) folders tree and all the files.
#### reuirements.txt
```
requests
bs4
lxml
```
Size calculation example

![](https://github.com/korzck/astralinux_file_parser/blob/main/code.gif)

To change loading directory you need to change `ulr` variable in `main.py` to correct path
