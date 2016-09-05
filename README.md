# The Czech Bar Association
Crawler of Czech Republic The Czech Bar Association.

Downloads HTML files, parsing them and produces CSV file with results.


## Requirements
* beautifulsoup4==4.4.1
* Ghost.py==0.2.3
* pandas==0.18.1
* PySide==1.2.4
* tqdm==4.8.4

##Usage

```
Usage: cak-crawler.py [options]

Options:
  -h, --help            show this help message and exit
  -o FILENAME, --output-file=FILENAME
                        Name of output CSV file
  -e, --extraction      Make only extraction without download new data
  -d DIR, --output-directory=DIR
                        Path to output directory
```
