# PDFman

PDFman is an application that attempts to search and summarize the content of your pdfs.

## Simple Analysis 11/11/2023
I have download three free books from https://manybooks.net:
- The Art of War
- The Phantom of the Opera
- A Brief History of the Internet

I want to first try some CLI tools available in Linux to see what is actually possible by just writing commands in Bash.

The first tool i want to investigate is called poppler-utils, in particular pdftotext program to extract text. 

On Ubuntu:
```
sudo apt-get update
sudo apt-get -y install poppler-utils
```
First command:

```
pdftotext resources/The-Art-of-War.pdf - | less
```
Print the text output on stdout in interactive mode.
