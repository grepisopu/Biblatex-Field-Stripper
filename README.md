# Biblatex-Field-Stripper
This program takes out undesired fields from a biblatex file

This file strips fields from a biblatex file. The orginal code was written by astrobel found here: 
https://forums.zotero.org/discussion/22629/bibtex-export-request-option-to-omit-certain-fields-for-less-cluttered-bibliographies  
I made the code more robust by modifying it to run from the command line, adding automatic outputfile creation, 
and taking in multiple fields to strip.

How to use is as follows:
1. run the program
2. enter the filename of your .bib file WITHOUT the extension
3. enter the name of the fields you want to strip. This is case senstitive!
4. Press q to stop entering new fields
5. Open your new biblatex file. The naming convention is <input filename>FIXED.bib