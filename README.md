# vim-plugin-install.bat

一个极简单的批处理脚本（仅一行），用来安装 Vim 插件（应急用）

A simple .bat script for installing Vim plugins (in an emergency)

```
for /f %%i in (%1) do git clone git@github.com:%%i.git
```

## 准备 / Preparation

能正常使用 Git 命令即可

## 用法 / Usage

在你的 Vim 插件目录下写一个文件，每行一个插件地址：

```
rakr/vim-one
romainl/vim-cool
Eliot00/auto-pairs
itchyny/lightline.vim
skywind3000/vim-auto-popmenu
```

存为 `list.txt` 文件（文件名任意），然后命令行执行：

```
install list.txt
```

## 没了 / That's All

Thank you.
