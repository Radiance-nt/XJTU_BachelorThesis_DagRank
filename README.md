# 毕业论文样例


使用模版来源[XJTU-Bachelor-Thesis-LaTeX-Template](https://github.com/1989Ryan/XJTU-Bachelor-Thesis-LaTeX-Template)，由西安交通大学校友 Zhao Zirui 等完成，感谢他的工作。

### 使用方法

将所有文件导入到overleaf上编译。
 - 进入该项目中，点击左上角“Menu/菜单”。
 - 将“Compiler/编译器”改成`XeLaTeX`，TeX Live 版本改为 `2020`


提交打印版时，任务书等材料上传至`pdf`文件夹，在`appendix/Materials.tex` 取消相关注释。

添加参考文献时，在google scholar中点击"引用, bibtex"，将内容复制进`bib/mybib.bib`，正文中添加`\cite{}`水平引用和`\upcite{}`上标引用（间接）。

添加表格时建议结合第三方网站 (如latex-table)进行生成，支持将Excel表格转latex代码。

### 论文内容

本论文提供内容及格式给大家参考，可以直接在此基础上进行修改,无需过多latex知识。

`main.tex`包含了`body/`目录下和`appendix/`目录下的各个`tex`文件，

论文内容见 `论文.pdf`，部分内容已做脱敏处理。
论文正文30页，篇幅较短，总评`A-`。

### 写作提示

本校毕业设计评阅时，评委老师组主要针对论文格式和篇幅长度进行审阅和提问。

arxiv上可以下载其论文的`tex`源码，论文里面公式及内容可以借鉴学习。

另外适当使用gpt辅助写作。比如：
 - "这篇论文使用了xxx方法，这样做有什么好处/为什么要这样做"
 - "写出与xxx方法类似的技术，并比较他们的优缺点"
 - "将下列latex代码翻译为中文，不改变其latex语法内容"
