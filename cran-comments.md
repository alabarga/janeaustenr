## Release summary

This is the first attempted CRAN release of janeaustenr, and my first submission to CRAN.

## Test environments
* Local OS X install: R 3.2.4
* Ubuntu 14.04 (on Travis-CI): R 3.2.4
* Win-builder: R-devel and R-release

## R CMD check results

0 errors | 0 warnings | 1 note

* The 1 note is for marked UTF-8 strings in data files; the texts of the novels are UTF-8 plain text.
* On Win-builder, there was a note for possibly invalid URLs for the Project Gutenberg URLs in the .Rd files because Project Gutenberg blocks automated traffic
* On Win-builder, there was a note for possibly mis-spelled words in DESCRIPTION (Austen's at 2:30 and 6:34, Northanger at 8:32) but these are the correct spellings