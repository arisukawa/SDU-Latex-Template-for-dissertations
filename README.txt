本latex模板改编自北大latex模板，适用于山东大学硕博毕业论文（格式已过盲审）。

山东大学论文规范 https://www.grad.sdu.edu.cn/info/1064/3372.htm

运行： 
XeLatex+bibtex(biber)+XeLatex+XeLatex

运行环境：
windows10
最新版本Texmaker以及完整版本的texlive

https://www.xm1math.net/texmaker/
https://www.tug.org/texlive/

然后Texmaker-选项-配置Texmaker
Bib(la)tex换成texlive中的biber.exe，
比如"C:/texlive/2021/bin/win32/biber.exe" %
XeLaTeX换成texlive中的xelatex.exe
"C:/texlive/2021/bin/win32/xelatex.exe" -interaction=nonstopmode %.tex

之后调好.bbl，.tex文件文件就可以玩耍了。.bbl很多网站的cite不能直接用，要把“”改成{}。
更多的细节可以参照北大模板pku1.8.2版本中的注意事项调整。也可以用ubuntu，细节见pkuthss v1.8.2原教程。
或者直接去北大bbs或者Email逮活人进行询问，因为北大模板有负责长期运营。
用的过程中如果有错误请先仔细修正texmaker中提示的error，warning和其他建议。如果页数太多可以先注释掉一些章节节约运行时间。
如果各个学院有其他细节要求可以在模板基础上进行更改。

latex 公式：https://latex.91maths.com/
latex 表格：https://www.tablesgenerator.com/
pkuthss v1.8.2：https://github.com/CasperVector/pkuthss/tree/v1.8.2
bbl玩崩了可以参考调整的细节：https://github.com/CasperVector/biblatex-caspervector

感谢北大多代人对pkuthss的努力运营有这么好的模板可以让我们抄（不是
祝各位山大学子毕业顺利=w=

by Arisukawa.



