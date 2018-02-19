# Quick PDF downloader #

Quick &amp; dirty tool to download multiple PDFs listed on an html webpage. All this can be done much more easily with a simple wget -r -A .pdf URL, but I had some time to kill and decided to reinvent the wheel a bit :-). 

## How to use ##
```
$./get_pdf [the_url_where_the_PDFs_are_listed] 
```
In case the files are not listed with the complete URLs, you can specify the base url as a second optional argument:

```
$./get_pdf [the_url_where_the_PDFs_are_listed] [base_url] 
```
Enjoy! :-) 
