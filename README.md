# iiserb-thesis-template
PhD thesis template for Mathematics IISER Bhopal (India)

--------------------INTRODUCTION--------------------------------------

This is the format for IISER Bhopal PhD thesis for Mathematics.
A modified version of the one originally prepared by Arghya Chattopadhyay. Huge shout out to Arghya for all the hard work!
The mathematics related changes are done by Rohit Dilip Holkar.


The formatting related contents (packages, custom layout, fonts, etc.) are now part of the IISERB.cls class file, which also contains the title page layout. 
All you have to do is enter your details in the individual details section in thesis.tex and edit included files. 

This version: 1.0.2

Update: 10 October 2023.

What is new: The title page and fonts there,  ToC and chapter headers modified as per
DoAA requirements. Style file for package tocloft added.
Thanks to Md Amir Hossain for designing the title page.

Modified and maintained for mathematics: Rohit Dilip Holkar.

Contact: rholkar@iiserb.ac.in

Created by: Sandeep Aashish

Contact: sandeepaashish@hotmail.com



--------------------COMPILING INSTRUCTIONS---------------------------------

COMPATIBILITY: pdflatex; bibtex; makeindex, xelatex (for indexing and nomenclature with nomencl package)

thesis.tex is the mainfile. Other included files (in folders: chapters, frontmatter, endmatter,commands) have a header: %!TEX root=../thesis.tex .

Most of the required .sty files are in styles folder. Add them to your local latex installation folder (if you don't know how, google it!). 

Bibliography style file hunsrt.bst is also in the styles folder.

On the first run, follow these steps:

pdflatex > makeindex thesis.nlo -s nomencl.ist -o thesis.nls > bibtex > pdflatex (x2)

You can add these arguments for makeindex in your editor's options menu.

===================================END========================================
