# ZoeeyDoc 介绍

ZoeeyDoc是一个DocBook文档构建工具，支持 single-html、html、chm、pdf 等格式导出。对中文支持良好。

## 优点

 * 纯文本格式：基于xml，纯文本格式方便版本控制。章节可分为独立的文件和目录进行编辑。

 * 多格式发布：经过一次书写便可以输出html、chm、pdf等众多格式，极大的方便了阅读。

 * 排版格式：排版格式精良。DocBook与专业排版工具TeX实力相当。常用来制作出版发行物、专业论文、软件手册等。

 * 格式规范：纯xml格式，有众多编辑工具，格式规范便于自动检验。

 * 中文支持：良好的中文支持自动引用系统字体生成pdf所需的字体描述文件。

 * 自动化支持：采用纯命令行形式，可方便的加入到各类自动构建工具中。

 * 人工服务：本地化，中文在线问题疑难解答。

 * 其他：生成single-html、html等格式会自动打包为zip文件。且zip、pdf、chm等文件会自动生成checksum 校验文件。

## 下载

[ZoeeyDoc-0.1.zip](https://github.com/eixom/zoeeydoc/raw/master/build/ZoeeyDoc-0.1.zip)

## 手册
| 格式 | 地址 | checksum| 备注 |
| :------------ |:---------------:|:-----:| -----:|
| chm  | [chm](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc.chm) | [checksum](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc.chm.checksum)| 无法查看：文件属性，解除锁定 |
| html  | [zip](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc.zip) | [checksum](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc.zip.checksum)|  |
| pdf  | [pdf](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc.pdf) | [checksum](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc.pdf.checksum)|  |
| single  | [zip](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc-single.zip) | [checksum](https://github.com/eixom/zoeeydoc/raw/master/build/zoeeydoc-single.zip.checksum)|  |



## 示例项目
http://code.google.com/p/cnphpdocs 【含文档源码、各格式下载】

http://code.google.com/p/yafphp     【含文档源码】

http://github.com/eixom/zoeeyphp  【含文档源码、各格式下载】
## 使用说明

```
========================
ZoeeyDoc help:
========================
-h/--help :
         打印此文档。

-c/--clean :
         清理缓存文件。

-t/--type :
         转换目标类型（chm,html,single/singlehtml），默认为 html。

-b/--book :
         文档目录。 文件配置文件为文件路径+"/config.kv"

获取帮助
java -jar ZoeeyDoc.jar -h

生成 html
java -jar ZoeeyDoc.jar -b docs/books/zoeeydoc -t html

生成 single html
java -jar ZoeeyDoc.jar -b docs/books/zoeeydoc -t single

生成 chm （需要指定hhc目录）
java -jar ZoeeyDoc.jar -b docs/books/zoeeydoc -t chm
```

## 参考资料
[DocBook](http://www.docbook.org/)

[DocBook XSL: The Complete Guide](http://www.sagehill.net/docbookxsl/index.html)

[ZoeeyDoc 使用技巧](http://blog.phploser.com/2011/03/12/zoeeydoc-docbook/)

## 其他
java运行所需：[JRE](http://www.java.com/en/download/index.jsp)

chm生成需要的hhc:[Microsoft HTML Help Downloads](http://msdn.microsoft.com/en-us/library/ms669985%28v=vs.85%29.aspx)

## 联系作者

email: system128 at gmail dot com

qq: 59.43.59.0

```
/*
 ________                                   
/\_____  \                                  
\/____//'/'    ___     __     __  __  __    
     //'/'    / __`\ /'__`\ /'__`\\ \/\ \   
    //'/'___ /\ \L\ \\  __//\  __/ \ \_\ \  
    /\_______\ \____/ \____\ \____\/`____ \ 
    \/_______/\/___/ \/____/\/____/`/___/> \
                                      /\___/
                                      \/__/ 
*/
```



## 以往版本
[http://code.google.com/p/zoeeydoc/](http://code.google.com/p/zoeeydoc/)
