# yonsei-thesis
Unofficial Yonsei University Thesis/Disseration Tex Template

**I will not be responsible for any consequences and losses caused by the use of this template**

I graduated in 2021. When writing a thesis in STEM, one almost has to prefer LaTeX, but there were either no templates or they were too unattractive, so I created my own. At that time, I was in a hurry to graduate, so even though I knew there were some issues, I left them unaddressed. But after hearing that many people are using it, I've updated it. Thank you to those who have used it. If there are any errors or operational issues, please register them in the issues.

생각보다 많은 분들이 써주신다는 이야기를 전해들었습니다. 부족한 템플릿임에도 사용해주신 분들 감사합니다.

* Accompanied with [VSCode LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) configuration
* **XeLaTeX(!!)** is highly recomemended
* It has not been tested in `pdfLaTeX.`.

# Requirements
* [Tex Live 2023](https://www.tug.org/texlive/)

# Fonts
* Body(Serif) : [Noto Serif Korean](https://fonts.google.com/noto/specimen/Noto+Serif+KR)
* Math : [TeX Gyre Schola Math](https://ctan.org/pkg/tex-gyre-math-schola?lang=en)
* Mono : [Noto Sans Mono](https://fonts.google.com/noto/specimen/Noto+Sans+Mono)
* CJK : [Noto Serif Korean](https://fonts.google.com/noto/specimen/Noto+Serif+KR)

# Known Issue

* luaLaTeX partially works but not be guaranteed
    - Hangul support is limited in luaLaTeX
* **pdfLaTeX doesn't work** due to conflict between `kotex` and `siunitx`
    - If you disable `siunitx`, this document can be compiled with pdfLaTeX

# Reference
* [Georgia Tech - Thesis Template](https://github.com/manoj-c/GATechThesis)
