# mk
|     key | description
|     ---:|:---
|  script | mk - a TeX and LaTeX maker
|    type | bash
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 3.09
| license | GNU General Public License

mk is a Bash script that, in close collaboration with vpp (short for
View and Print PDF/PostScript), is helpful in the cyclic process of
editing, compiling, viewing, and printing a tex document. Essentially,
mk uses texi2dvi for compilation, vpp for viewing and printing. Any
TeX formatter can be handled, with the exception of those starting
with ht (such as httex and htlatex) and context (handle those with
texexec).
