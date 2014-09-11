OU-LaTeX-TMA-package
====================

http://learn1.open.ac.uk/mod/forumng/discuss.php?d=5940#p59362

I don't believe this is an 'Offical' Open University LaTeX package.

Thsi is how *I* installed it on OSX 10.9.4 after I had installed MacTEX-2014 

	$ mkdir ~/Library/texmf/
	$ mkdir ~/Library/texmf/tex
	$ mkdir ~/Library/texmf/tex/latex
	$ mv tma.sty ~/Library/texmf/tex/latex
	$ open ~/Library/texmf/tex/latex
	$ mkdir ~/Library/texmf/doc
	$ mkdir ~/Library/texmf/doc/tma
	$ mv notes.pdf ~/Library/texmf/doc/tma
	$ mv notes.tex ~/Library/texmf/doc/tma
	$ mv SampleTMA.pdf ~/Library/texmf/doc/tma
	$ mv SampleTMA.tex ~/Library/texmf/doc/tma

I also put SampleTMA.tex and notes.tex in template folders

For TeXwoks ~/Library/TeXworks/templates/My Templates

For TeXShop in both ~/Library/TeXShop/Stationery and ~/Library/TeXShop/Templates

Note - I tried putting texmf in ~ (~/texmf) first, which would work on Linux or another Unix, but OSX 10.9 required 'texmf' to be in ~/Library folder (~/Library/texmf).


