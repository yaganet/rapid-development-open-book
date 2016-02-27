# Rapid Development Open eBook
The approach is to write together an (open-source) book that gives an overview about technologies for rapid development. The choosen format is asciidoc (for merging purposes).

Latest HTML:
https://htmlpreview.github.io/?https://github.com/oliverkarst/rapid-development-open-book/blob/master/readme.html


## How to generate the eBook(s)
For the format with the extension adoc you need the utility asciidoctor. For retrieving and installing it please refer to the web (google search). Asciidoctor provides the formats html and docbook.

In case you would like generate a PDF version you will need to install the utility asciidoctor-pdf. Again please refer to google search how to install that.

After you installed the both utilities asciidoctor and asciidoctor.pdf invoke simply
[source]
./generate_docs.sh
