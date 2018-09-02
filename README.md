student_paper
=============

Computer science books and papers written by a group of PetrSU students.

[Petrozavodsk State University](https://en.wikipedia.org/wiki/Petrozavodsk_State_University) (PetrSU), Internet-mathematics course.

# Scratch book (in Russian)

See our course [Scratch](https://ru.wikiversity.org/wiki/Scratch) in Russian Wikiversity.

## Quick Start

The Scratch book (file `student_paper/scratch/s1book.tex`) can be compiled with the following:

    pdflatex s1book
    bibtex s1book
    makeindex s1book.idx
    # or texindy --language english s1book.idx
    pdflatex s1book
    pdflatex s1book
    pdflatex s1book

The result should look like `s1book.pdf`.

## Troubleshooting

If you encounter errors of the form,

    ! LaTeX Error: File `paralist.sty' not found.

you will need to obtain missing packages from [CTAN](http://ctan.org).
For package installation instructions and answers to many other
questions, see the [UK TeX FAQ](http://www.tex.ac.uk/faq/) or search the [`comp.text.tex` group](http://groups.google.com/group/comp.text.tex).

The template of [Tufte-LaTeX](https://github.com/Tufte-LaTeX/tufte-latex) GitHub project used.

# Literature

   * Krizhanovsky, Andrew (2015) [Methodology and guidelines of writing articles in Wikipedia by students with the help of the teacher (the Russian Wikipedia case study)](http://nauchkor.ru/pubs/rabota-v-viki-srede-na-primere-russkoy-vikipedii-5690f7f35f1be74d9400018e) (in Russian). Petrozavodsk. (preprint). 
.
