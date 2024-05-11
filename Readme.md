# 文件说明

当前配置: \_vimrc\_240511
运行环境：win10，gvim

个人用vimrc配置，仅供参考。
目前包括以下功能：
vimtex 配合 SumatraPDF 进行 vim 上的 tex 编辑，目前可能有一些问题。

其他内容：

引用了preservim/nerdtree插件，可用于查看文件目录。打开vim自动开启Nerdtree

中文环境配置：
~~~
set guifont=Courier\ New:h12
set guifontwide=霞鹜文楷等宽:h13
~~~
需安装对应字体，否则需要修改对应内容。

自动折行和按屏幕行滚动屏幕

不产生交换文件，不设置备份文件

共享剪贴板

光标移动均映射为软换行，包括jk和上下键。