# digital-collections-sync
Sync digital collections content to AWS S3 honoring ignore list and validating fixity.


![](header.png)

## Installation

Linux:

```sh
npm install my-crazy-module --save
```

## Usage 

Usage: digital-collections-sync [options] [path]

Options:
  -a, --all                 equal to -ir
  -h, --help                show this help message and exit
  -f FILE, --file=FILE      read file paths and fixity from FILE
  -i, --ignore              ignore files listed ignore files listed
  -l FILE, --log=FILE       write verbose log to FILE
  -p, --path                AWS S3 storage path
  -r, --remote              compare fixity between local storage and AWS using MD5
  -v, --verbose             print verbose output to stdout

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.


