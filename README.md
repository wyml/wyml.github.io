>此Blog使用WyY Blog Editor生成并部署
>
>下载地址：[Download](https://pan.kingsr.cc/s/9jsmd70c)
>
>文档地址：[WyYBE文档](https://be.kingsr.cc/)

# WyY Blog Editor

## 简介

WyYE是一款用易语言配合JS编写的一款静态BLOG生成器。他的工作方式类似于Hexo，能够在一定情况下配合JS或者DLL配合生成静态博客。
同时支持部署至Github、Gitee等Git托管网站上。

## 如何使用

### 0x00：配置文件

打开/config文件夹，复制一份`.example.base.json`重命名为`base.json`并按照内容修改好。

### 0x01：开始写作

打开根目录下的`WyYBlogEditor.exe`主程序。在上方选择“写作中心”即可开始写作！写作完成后按`Ctrl+S`保存文章。**文件标题即为文章标题！**
![1.png](https://i.loli.net/2020/02/01/xC9zwidU2sLghOZ.png)

### 0x02：部署博客

写作完成后关闭窗口返回主界面，点击主界面“站点管理>编译”按钮即可自动完成部署。需要注意：本功能需要Windows下安装Git并已经进行关联设置。
![2.jpg](https://i.loli.net/2020/02/01/a6Pc3K8snyxAETV.jpg)

### 0x03：小技巧

在config目录下，conf.ini文件为程序配置文件，其中`ShowDOS`为显示DOS执行窗口*窗口仅可读*你可以将其设置为`ShowDOS=1`开启；`AbsoluteUrl=1`为将编译地址转为绝地地址，及将主题中的`{$assetsPath}`渲染为`base.system.url`。

![3.png](https://i.loli.net/2020/02/01/gbytDE4FiQxWuTS.png)

## 自建主题

*等待编写*

## 联系我

- mail：i@kingsr.cc
- QQ Group:165765356
- QQ:1143524493