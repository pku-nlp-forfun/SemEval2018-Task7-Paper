# SemEval2018-Task7-Paper

Paper for PKU NLP course report.

## Compile

```sh
bibtex main
```

```sh
pdflatex main
```

## Trouble Shooting

### fontspec package

```txt
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!
/usr/local/texlive/2016/texmf-dist/tex/latex/fontspec/fontspec.sty:28: Fatal fontspec error: "cannot-use-pdftex"
!
! The fontspec package requires either XeTeX or LuaTeX.
!
! You must change your typesetting engine to, e.g., "xelatex" or
! "lualatex"instead of plain "latex" or "pdflatex".
!
! See the fontspec documentation for further information.
!
! For immediate help type H <return>.
!...............................................
```

```sh
# Use this command to compile
xelatex main
```
