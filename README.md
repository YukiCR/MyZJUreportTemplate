## MyZJUreportTemplate

> See also: 
> [ZJUreport](https://github.com/haochengxia/zjureport)
> [UCAS_Latex_Template](https://github.com/jweihe/UCAS_Latex_Template)

### Intro
A simple $\LaTeX$ templete for reports of ZJU, developed from [ZJUreport](https://github.com/haochengxia/zjureport) with some minor changes:
+ Use `GB/T-7714` standard for citation with the [gbt7714](https://ctan.org/pkg/gbt7714) package 
+ Use `enumitem` package instead of `enumerate` for better flexibility
+ Use `subfig` package instead of `subfigure` package, since the latter is a relatively old package
+ Use `AutoFakeBold` and `AutoFakeSlant` for better bold and italic font support
+ Minor changes according to *my* aesthetic taste 

### Use this template
+ just follow the instructions of [UCAS_Latex_Template](https://github.com/jweihe/UCAS_Latex_Template), use the recipe `xelatex->bibtex->xelatex` for compiling the [tex file](./main.tex)
+ if you are using this template with `VSCode` + `LaTeX workshop plugin`, refer to [latexWorkshopSettings.json](./latexWorkshopSettings.json) for the plugin settings 