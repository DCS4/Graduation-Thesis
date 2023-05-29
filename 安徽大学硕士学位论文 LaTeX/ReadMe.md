

> 本项目改自[安徽大学硕士学位论文LaTeX模板](https://github.com/Monoceros393/AHUThesis)，主要改了buaa.cls文件中的格式。本文所展示文件为最终提交至图书馆版本。

## 项目地址
[Github](https://github.com/DCS4/Graduation-Thesis)
## 文件说明

```
<文件目录>          
├── bst                     # 存放参考文献格式文件 
    ├── GBT7714-2005.bst    # 2005版国标格式文件
    ├── GBT7714-2015.bst    # 2015版国标格式文件（默认使用）
├── contents                # 存放文件，用于替换插入论文某一页文件
    ├── declaration.pdf     # 导师签过字的独创性声明文件，直接替换即可引入
├── pic                     # 存放论文所需图片（eps、png、pdf、... 格式）
    ├── work1               # 存放工作一所用图片
      ├── xxx.pdf
      ├── xxx.pdf
    ├── work2               # 存放工作二所用图片
      ├── xxx.pdf
      ├── xxx.pdf
    ├── cover.eps           # 首页蓝色封皮
    ├── head-doctor.png     # 博士学位论文标题图片
    ├── head-master.png     # 硕士学位论文标题图片
    ├── head-professional.png # 专业硕士学位论文标题图片
    ├── logo-ahu.png        # 首页安大学校logo
├── tex                     # 存放正文的tex文件
    ├── chapterxxx.tex      # 第xxx章内容
    ├── References.tex      # 存放参考文献的文件（手动引入参考文献）
├── buaa.cls                # 定义论文的样式文件  
├── Main.pdf                # 论文pdf文件
├── Main.tex                # 论文主文档
├── ReadMe.md               # 使用说明文件
├── ref.bib                 # 存放参考文献内容（自动引入参考文献）
├── simhei.ttf              # 黑体文件
├── simsun.ttc              # 宋体文件
```

## 使用注意事项
1. 字体格式
> overleaf中使用的宋体、黑体字体和window上不一致，所以上传windows自带的字体文件（simhei.ttf、simsun.ttc），本地环境未测试。

2. ==编译设置==
> overleaf编译选项选为==XeLaTex==，选择pdfLaTex无法正确生成pdf。
>
3. 参考文献引用
> 有两种引用格式：（一）将引用参考文献写入`ref.bib`文件 主文件中加入命令`\Bib{bst/GBT7714-2015}{ref}` （二）参考文献写入`References.tex`文件 主文件中填写 `\bib ....`
5. 英文缩写(Differentiable Rendering,DR)  ，数学公式用英文逗号  否则会出错。

## 使用说明
1. 论文提交图书馆时，需要蓝色封皮。
2. 盲审时，打开盲审模式，去掉致谢。
3. 论文具体格式如间距、字体并没有严格规定，最后单面打印即可。
4. 独创性声明只需替换cover.eps。
5. 图片中的字体英文为新罗马体，中文用宋体，字号大小没要求，中英文都可以。


## 本人运行环境
Overleaf在线编辑器
