#ACM Cheat Sheet
-----------------
##PDF下载
<a href="https://github.com/soulmachine/acm-cheat-sheet/blob/master/C++/%E6%89%8B%E5%86%99%E4%BB%A3%E7%A0%81%E5%BF%85%E5%A4%87%E6%89%8B%E5%86%8C(C++%E7%89%88).pdf?raw=true">ACM Cheat Sheet(C++).pdf</a>

1. C 文件夹下是C版
1. C++ 文件夹下是C++版
1. Java 文件夹下是Java版

##编译环境
1. 安装Tex Live 2013 <http://www.tug.org/texlive/>。注：TexLive适用于Windows/Unix/Linux/MacOS.
1. 安装字体。这个LaTex模板总共使用了9个字体，下载地址 <http://pan.baidu.com/s/1gdefYiJ> ，有的字体Windows自带了，有的字体Ubuntu自带了，但都不全，还是一次性安装完所有字体比较方便。
1. 安装TeXstudio <http://texstudio.sourceforge.net/>
1. (可选)启动Tex Live Manager，更新所有已安装的软件包。
1. 配置TeXstudio。

    启动Texstudio，选择 `Options-->Configure Texstudio-->Commands`，XeLaTex 设置为 `xelatex -synctex=1 -interaction=nonstopmode %.tex`；

    选择 `Options-->Configure Texstudio-->Build`

    Build & View 由默认的 PDF Chain 改为 Compile & View；

    Default Compiler 由默认的PdfLaTex 修改为 XeLaTex ；

    PDF Viewer 改为 “Internal PDF Viewer(windowed)”，这样预览时会弹出一个独立的窗口，这样比较方便。

1. 编译。用TeXstudio打开`crackcodinginterview.tex`，点击界面上的绿色箭头就可以开始编译了。

    在下方的窗口可以看到TeXstudio正在使用的编译命令是`xelatex -synctex=1 -interaction=nonstopmode “crackcodinginterview”.tex`
