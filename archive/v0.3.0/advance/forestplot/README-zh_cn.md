## [森林图](/advance/forestplot)

- ### 功能介绍

  除meta分析外，森林图还广泛应用于观察研究和临床试验，如风险分析/生存分析。

- ### 数据结构

  需要两张表格数据。

  \<第一张表格数据\>：

  \<第1列\>：（数字）平均数据

  \<第2列\>：（数字）下部数据

  \<第三列\>：（数字）上部数据

  \<2nd table\>：（字符串或数字）文本表。


- ### 参数详解

  **上传|下载**

  Browser: 用户本地电脑文件读取并上传

  Example Download: 示例数据下载

  Result Download: 结果图像或者所有文件压缩下载

  Width: 输出图像的宽度（默认为英寸如标准为12 x 7 inch）

  Height: 输出图像的高度（默认为英寸如标准为12 x 7 inch）

  DPI: 图像分辨率（默认300dpi为较高图像质量）

  Format: 图像格式选择，所有图像提供PDF，PNG等主要科研需要格式

    **计算|绘图**
    
    Title: 图像的标题，可以替换图像默认的标题
    
    Theme: 图像的主题，由ggplot2提供多种个性化主题
    
    Font Family: 字体（如主流期刊规定的Time New Romas）
    
    Alpha: 元素的透明度（0-1，0表示透明，1表示不透明）
    
    
    Legend Position: 图例在图像中的位置
    
    Legend Direction: 图例中多个元素的排列方式（横向或纵向）
    
    Legend Title Size: 图例主标题大小
    
    Legend Text Size: 图例中元素文本的大小
    
    
    Axis Title Size: 图像坐标轴标题的大小
    
    Axis Font Size: 图像坐标轴刻度字体的大小
    
    Axis Text Angle: 图像坐标轴文本的角度
    
    Axis Adjust: 图像坐标轴文本的距离（微调）
    
    
    **特殊参数**
    
    程序分析内容参数：具体算法或实现可参考核心模块官方说明文档
    
    参考我们平台针对复杂程序上线的详细教程视频：https://space.bilibili.com/351815613
    
    主要美化参数：https://ggplot2.tidyverse.org/reference/
    
    更多特殊参数可以参考：https://ggplot2.tidyverse.org/reference/theme.html

- ### 引用模块

  forestplot: (Maintainer: Max Gordon \<max@gforge.se\>)
