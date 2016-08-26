# Just Another Beamer Template
You don’t want to create an another ordinary Beamer presentation, do you? Despite you changed the colour theme, everyone immediately knows it’s been made in LaTeX, everyone knows those templates. I am not saying it’s wrong (a lot of my slideshows looked like that) but might you consider using a template looking different? How much different? Have a look at my first Beamer template! I hope you will enjoy it!

# Requirements
The template uses two non-standard fonts. Both of them are free. You can clone the fonts from here or download them from dafont.com:

1. [Libel Suit](http://www.dafont.com/libel-suit.font)
2. [Chinatoo](http://www.dafont.com/chinatoo.font)
*Note that fonts are required at compilation stage only as lualatex includes the fonts into result pdf file.*

# Installation
1. Install the fonts
2. Extract the template files. The template needs to be in directory visible by LaTeX. If you want to just try out the template, place *.sty files together with your *.tex file. To not copy the template each use, you may put the template in LaTeX directory. In case of MiKTeX, move *.sty files to appropriate subdirectories of MiKTeX 2.9\tex\latex\beamer\base\themes\theme. The template consists of 4 files:
    * beamercolorthemeWronki.sty
    * beamerinnerthemeWronki.sty
    * beamerouterthemeWronki.sty
    * beamerthemeWronki.sty
The 5th file - [Wronki-example.tex](https://github.com/kangur85/wronki/blob/master/Wronki-example.pdf) – is an example slide show.

# Compilation
The template needs to be compiled using **lualatex** – as far as I know, it’s a pdflatex with support of system fonts and Unicode. A compilation does not differ from pdflatex:
```sh
lualatex Wronki-example.tex
```
# Extra commands
* \kTitleFrame – Inserts a title frame
* \kTOCFrame{Title} – inserts a table of contents with a given title
* \kSectionFrame – the command may be used to create a frames being displayed (before each section or subsection, for example). There is also a few background images predefined. Look at the example and study beamerinnerthemeWronki.sty for more. The used images are actually single Chinatoo font’s letters.
* \kQuestionsFrame – end frame with some additional banners on the bottom.

# Why is it named Wronki?
Standard Beamer templates are named for capitals’ names. Well, Wronki is not a capital but it’s a town where I grew up so I thought it would be cool to show my love in that way... :-)

Real example

# Licence
It’s free to modify and redistribute. But please be aware it’s my first template and I’m not a Latex guru at all. Most probably, there is a lot of bugs. It works for me, though.

