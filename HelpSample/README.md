# CHMReader

CHMReader is a WPF application that reads contents from a CHM help file. The sample illustrates two methods for achieveing the same.

## Method 1

Using [HtmlHelp library](https://www.codeproject.com/Articles/6765/HtmlHelp-library-and-example-viewer). The library has a method which supports searching for a particular URL in CHM file using key words. The URL is then loaded into a WebBrowser

## Method 2

Exracting HTML files from CHM into a target folder and manually finding the required file through recursive directory search. The file is then loaded into a WebBrowser.