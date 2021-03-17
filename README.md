# R markdown学术写作

## 为什么要学R markdown? 我给你10个理由

Rmarkdown学术写作的优势一句话：all in one。

1个Rstudio可以把学术写作的所有要素全部集中，不需要额外的软件。一个R markdown文件，一个完整的workflow，完全复现你写作中的方方面面。从写作到发表一条龙服务。

1.	支持markdown语法，可以分享在任何支持markdown语法的博客和Github上。Markdown基本语法5分钟左右即可掌握，不会出现乱七八糟的格式，避免了word各种繁琐的格式调整。
2.	所有的数据分析都可以在写作中，边写边呈现结果。可以随意定制，如是否显示输出结果、是否显示图片，是否显示代码。随意控制输出的样式，如图片大小、坐标样式。臃肿的SAS、SPSS、Stata几乎都可以抛弃（Rstudio具备优秀的数据分析和可视化包）。
3.	不需要额外的参考文献管理工具，最新版的Rstudio 1.4默认集成了文献管理，支持Bib文献库（即Bibtex）。参考文献的style史上最全，兼容CSL的style，随意切换，快速达到投稿要求。
4.	几乎覆盖了所有出版集团的写作模板（如Elsevier，springer，MDPI等）。
5.	支持除R以外的其他编程语言，如Python、SQL、D3、Rcpp（C++）等。
6.	支持LaTeX的排版和语法。
7.	支持输出几乎所有主流的格式，包括html/pdf/docx/pptx/md等。
8.	适应任何写作目的：manuscript、book、presentation、blog、CV、post。
9.	更好的协作性。自带git模块，版本管理，团队协作游刃有余。
10.	几行代码自动生成美观的表格，Table one 和OR可以通过相应的包自动测算并输出。


### 介绍
Rmarkdown学术写作课程（医咖会）

### 适用人群
科研工作者、研究生、数据科学从业者等


### 课程大纲

#### 第一章 准备工作与理论

1.  Rmarkdown是什么（生态、作者、历史），可以做什么
- 写论文
- 写书
- 写毕业论文
- 写学术墙报
- 写简历
- ...
2.  Rmarkdown写作的优势（相较于word、jupyter notebook）
- all in one (即将写作和统计分析、作图融合在一起，一个程序解决所有问题)
- 兼容markdown语法、可以运行除R以外的代码（python、SQL等）
- 可以将文档转化成各种常见格式，便于发布和整理
- 可以和git融合，方便版本控制，天生开源特性
- 丰富的模板和自动化操作
3.  Rstudio的安装、设置和包管理
- Rstudio的安装及注意事项
- Rstudio的设置
- 包管理（内置方法、devtools、remotes、pacman）
4.  Rmarkdown需要安装的包
- tinytex
- rticles
- tidyverse
- bookdown
5.  Rmarkdown的结构及工作原理
- Rmd文件结构（yaml、text（markdown、latex）、chunk option、code chunk）

#### 第二章 基础操作与参数讲解

1.  yaml头部及参数
- yaml this包快速设置
- yaml语法注意事项
- 常见参数设置title|author|output|toc|template|reference等
2.  markdown语法速成（10分钟）
3.  chunk（代码块）
- 插入代码块（R和python演示）
- chunk option
4.  表格
- 表格使用的包（flextable、kable）
- 和我一起Table one
5.  图片
- chunk文档内生成图片
- 外部图片
6. 文档拆分与合并
7. 引用
- csl及引文样式
- 配合参考文献管理工具（jabref、endnote、zotero）
- 参考文献引用（1.4版本说明）
- 文档内部引用（引用图片、表格或某章节）
8. 一些格式操作
- 分页
- header latex设置和模板
- 首行缩进
9. 输出操作
- pdf
- word
- html

#### 第三章 实战学术写作
1.实战
- 写一个完整的manuscript
- 关于rticles包
- 写一个post（postdown包）
- 写一本书，以[R Markdown Cookbook](https://github.com/yihui/rmarkdown-cookbook)这本开元书籍为例
- 写一个学术简历（vitae包）
2. 结语
- 我的一些理念
- 对R的未来畅想
- 致谢

### 关于作者
梁昊，工作于湖南中医药大学中医诊断研究所  医学博士，讲师，主治医师。

半个码农，后半生准备投身医学人工智能。临床擅长诊治心血管疾病及儿科疾病，尤其对失眠、久咳、小儿遗尿治疗颇有心得。

