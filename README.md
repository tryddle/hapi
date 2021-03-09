# conlangs
--------------------------
Hello dear visitor!

My name's tryddle, I'm a conlanger and in this repository I will upload monthly updates on my conlang *Hapi*, or more specifically, on its documentation. I've been conlanging for about 3½ years now and it's always been dear to my heart. I write my reference grammar using the markup language LaTeX, which I can recommend to everyone, as it produces beautiful documents. I might also add other conlangs in the future, but right now I'll be concentrating on aforementioned *Hapi*. In this repository you will find a) a pdf file and b) its LaTeX source code, so you can see how to produce the examples/tables/etc. in the pdf.¹ Some information on how to use LaTeX for conlanging:

## How to: Conlanging using LaTeX
### XeLaTeX
To render IPA characters in LaTeX, in my opinion the best way to do it is using the typesetting engine XeLaTeX. Most if not all IPA characters and diacritics will render using it; if you want to know how to input IPA characters into your document, I suggest you check out [WinCompose](http://wincompose.info/), a small program with which you can enter custom characters very easily. Another alternative to XeLaTeX is the package [tipa](https://www.tug.org/TUGboat/tb17-2/tb51rei.pdf), which albeit not recommendable might be the preferred choice of beginners. Nevertheless in my experience, XeLaTeX is far more handy than tipa.

### Glossing packages
An interlinear gloss is a way to convey grammatical information of any language to the reader ([The wikipedia page](https://en.wikipedia.org/wiki/Interlinear_gloss) has some examples). There are multiple packages to create such glosses in LaTeX:

* [gb4e](http://tug.ctan.org/macros/latex/contrib/gb4e/gb4e-doc.pdf)
* [expex](http://mirrors.ibiblio.org/CTAN/macros/generic/expex/expex-doc.pdf)
* and finally, baarux

Having tried all three of them, I can say that baarux is the most versatile of them all. Alas, it is not available for the public, and until its creator publishes it, gb4e or expex are good enough alternatives.

Obviously all of this is still heavily WiP.

Cheers!

¹Disclaimer: the code is partially very ugly and I'm sure there are some ways in which I can improved it. If you find something that I should revise, let me know!
