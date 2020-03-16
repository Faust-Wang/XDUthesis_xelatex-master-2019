# What is XDUthesis_xelatex?

XDUthesis_xelatex is an *unofficial* XeLaTeX template for preparing bachelor, master, or doctor thesis in Xidian University.

# 西安电子科技大学学位论文LaTex模板

本模板根据西安电子科技大学研究生院发布的[研究生学位论文模板（2015版）](http://gr.xidian.edu.cn/system/_content/download.jsp?urltype=news.DownloadAttachUrl&owner=1281831001&wbfileid=2041391)修改而成，并满足其规定的格式要求。研究生院官方发布的模板编译方式为latex，采用GBK编码，仅支持CTeX(2.9.2)。官方模板部分语法老旧，本模板修正了其中存在的一些问题，并且支持xelatex编译，使用时更为便利。模板采用UTF-8编码，支持Linux和TeX Live 2016，TeX Live 2017，TeX Live 2019。
由于旧版本模板跟学校最新的模板相比有些许不同，对一些不熟悉LATEX的同学来说修改有些困难，故做出以下修正，使之与学校最新（截至2019年6月）的模板同步。

***声明：此模板是本人在睿思下载到的模板基础上修改的，睿思上帖子注明其原GitHub链接在：https://github.com/103yiran/XDUthesis_xelatex （我也不知道该GitHub是不是原作者）***

1.此处修改“二级学科”为“二级学科（研究方向）”，同时全部加上了冒号（与官方相同）。
![image](https://github.com/Wangfakui/XDUthesis_xelatex-master-2019/blob/master/figures/1.jpg)

2.此处修改“Thesis”为“thesis”，同时谨记2019届毕业论文模板英文处的学科是你的一级学科名称（以前的时候是你的二级学科）。![image](https://github.com/Wangfakui/XDUthesis_xelatex-master-2019/blob/master/figures/2.jpg)

3.此处修改论文的分割线，原先模板是没有对齐的，现已按照学校官方模板的样子对齐了。![image](https://github.com/Wangfakui/XDUthesis_xelatex-master-2019/blob/master/figures/3.jpg) ![image](https://github.com/Wangfakui/XDUthesis_xelatex-master-2019/blob/master/figures/4.jpg)

4.此处将加粗单线修改为双线（与官方同步）。![image](https://github.com/Wangfakui/XDUthesis_xelatex-master-2019/blob/master/figures/5.jpg)


## 如何使用

* 本模板的默认封面为工学硕士封面。

* 论文和作者的相关信息可在XDUthesis.cfg文件中进行修改。

* 参考文献在./bib/tex.bib文件中录入。百度学术和谷歌学术均支持BibTeX格式导出，但其中夹杂很多不规范的条目，应注意进行检查。


## 系统需求

本模板需要使用 XeTeX 引擎编译。Linux下编译时需首先配置windows系统中提供的SimSun和SimHei字体。模板验证无问题的平台为Debian 8 和TeX Live 2016，TeX Live 2017，TeX Live 2019。

## 已知问题
使用XeTeX时，AutoFakeBold选项导致复制乱码。模板中在`\begin{document}`后插入一个日文的空格'　'，使得除章节一级标题外其他内容可复制。

## 查重问题
本模板生成的PDF在知网查重符合学校标准，不会产生乱码。如若出现任何查重问题，本人概不负责。

