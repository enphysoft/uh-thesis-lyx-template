# uh-thesis-lyx-template

This git-hub site provides an Lyx template for graduate students in the University of Hawaii. 
The template is made as it contains minimum contents of each necessary items from Mr. Tyler Tsuchida's master thesis in 2019.  
The template was developed by using LaTex template (https://github.com/rbrewer/latex-uhm-thesis) by Dr. Robert Brewer at Collaborative Software Development Laboratory, University of Hawaii at Manoa. 

## Usage

### Layout installation
Go to "layout" directory and read INSTALL.org.
If you have a root authority in Linux system, you can follow the direction.
Otherwise, include the layout as a "local layout" in Lyx program.


### Lyx compilation
The main file is "uhthesis.lyx", which contains child lyx files of all other .lyx file. 
Chapter lyx files (Chapter1_Introduction.lyx, Chapter2_ManholeCFD.lyx, Chapter3_CanopyCFD.lyx, and Chapter4_Conclusion.lyx) and included in the main lyx file in a sequence and all other files (my_abstract.lyx, my_acknowledgments.lyx, my_appendix.lyx, and my_dedication.lyx) are prepared as needed.

Compiling uhthesis.lyx will generate uhthesis.pdf, which can be sumitted to UH Graduate Division as it is. 

Within "uhthesis.lyx", several bibtex files (of .bib in bib directory) are called and only some of items are cited into the Lyx file. 

In bst directory, there are specially developed bibstyle file (.bst), which can be used to generate references, if you want clean, short, and minimum reference list (wihtout doi and url links). 

In Figures directory, all the figures are separately stored, which are included in the file pdf. 

## Resources
- Lyx: LaTex-based WYSIWIM (What You See Is What You Mean) editor
Introduction to Latex and Lyx: Part 1, 2, 3, 4, and 5
https://www.youtube.com/watch?v=m4cEAVmLegg&feature=youtu.be

LaTex
MacTex (download)
MikTex (download): LaTex/Tex for Windows
Editor for LaTex: TEXnic Center (Win), WinEdt (Win), TeXShop (Mac)
Getting Stared with LaTex
Computer Science, Cornell University
Mathematics Department, Elon University
Bibliography library: Natbib
Roger’s online equation editor
Templates for
REVTex: Macro-packages designed to be used with LaTex2e for APS publication
Elsevior journal publication, elsarticle class (download elsarticle.zip)
beamer presentation (matrix), poster
Commercial converting software by http://www.grindeq.com:
LaTex-to-Word and
Word-to-LaTex
PDF Labs
 pdftk (PDF Tool Kits): download and install, examples
