# BibCleaner


This is a simple Rmd file that takes a bibtex file and a tex file and removes all references from the bobtex that are not in the tex document, the cleaned bibtex is then saved back to the original folder. 

I created this markdown file becuase often when writing papers the entire library of references for all work ever is included in the bibtex. However, when submitting to the journal only the relevan references can be included. This script solves the cleaning process.

## Notes:

When the script finds an error it will through an error in the function. I have written another function which allows you to identify the entry that is causing the issue so that it has can be manually corrected. However, I don't know how to get the function to find all the errors at the same time so they can be fixed simultaneously. Any hints would be appreciated!
