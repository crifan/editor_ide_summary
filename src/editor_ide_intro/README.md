# 编辑器和IDE简介

在作为普通电脑用户和技术人员开发期间，往往会用到很多工具软件，去编辑代码文件，开发和调试项目代码。

在此期间，用于编辑文件和调试项目的工具，就是此处要介绍的：

* `文本编辑器`=`Text Editor`
  * 简称：`Editor`=`编辑器`
  * 主要用途：
    * 普通用户：`编辑文本文件`
    * 开发人员：`编写代码`
* `IDE`=`=Integrated Development Environment`=`集成开发环境`
  * 主要用途：
    * 开发人员：`编写代码` + `调试代码`

对于**编辑器**和**IDE**，先总结宏观概况，再解释微观细节：

## 编辑器和IDE的分类

宏观上说，有多种不同角度去分类编辑器和IDE，同时附带简易的举例和说明：

* 根据**功能强弱**去分
  * 编辑器=Editor
    * 举例
      * Win中最简单的：`记事本`
      * Mac中最简单的：`文本编辑`
      * Win中相对通用的编辑功能的：`Notepad++`
      * Win中用于开发方面的查看Linux内核源码的：`Source Insight`
  * 集成开发环境=IDE
    * 解释：
      * IDE=集成开发环境
        * **集成**：在普通的（编辑文件的）编辑器基础上，额外加上了 其他开发所需功能
          * 谓之：集成
          * 其他开发所需功能 包含哪些：
            * **编译器**=`compiler`
            * **调试器**=`debugger`
            * **版本控制系统**=`VCS`：比如`svn`，`git`等
            * **图形用户界面**=`GUI`
            * 集成其他工具
              * **终端**=`Terminal`
              * 等等
            * 等等
          * **开发环境**：主要用于技术开发领域，调试某些编程语言的代码
    * 举例
      * Win中通用的IDE：`Eclipse`
      * Mac中开发Python的：`PyCharm`
  * 额外说明：
    * 现在的Editor和IDE的**边界越来越模糊**了，尤其像VSCode这种，作为编辑器功能足够强大，加上各种插件后，可以称之为IDE了
* 根据**是否需要网络**去分
  * 本地的离线的编辑器或IDE
    * 比如目前**大多数**的编辑器都是安装到本地电脑上即可使用，**无需网络**
  * 在线的云端的编辑器或IDE
    * 比如新出现的一些编辑器或IDE，需要有网络，通过浏览器去使用，属于远程的云端的在线编辑器或IDE
  * 额外说明
    * 部分工具，如`VSCode`既支持本地离线，又支持云端在线
* 根据**支持的平台和系统的多少**去分
  * 不少编辑器和IDE，支持多种平台和系统，称为：**跨平台**
    * 比如
      * VSCode支持Win，Mac，Linux等多种平台
  * 有些编辑器和IDE，只支持特定的平台和系统，不支持跨平台
    * 比如Notepad++只支持Win平台
* 根据**不同编程语言**去分
  * 很多编辑器或IDE，是专门针对某些编程语言的
    * 比如
      * 专门只支持一种语言Python的`Spyder`
  * 有些编辑器或IDE，是相对通用的，支持更多，更广泛的语言
    * 比如
      * `JetBrains`旗下的`PyCharm`，虽主要针对Python设计的，但是也支持其他如JS，HTML，CSS等Web领域的开发
* 根据**功能是否支持扩展**去分
  * 支持扩展：有些通用的编辑器或IDE，通过插件支持更多其他编程语言
    * 比如`Eclipse`，是个通用的IDE，通过插件`PyDev`可以支持调试Python
  * 不支持扩展：其他更多的编辑器或IDE，功能是固定的，往往只针对单个或某个领域的编程语言
    * 比如`WebStorm`，主要针对于JS语言和相关的Web领域
      * 虽然WebStorm也支持插件机制，但是主要是安装一些小的功能，其本身的开发和调试的语言，还是侧重在Web领域和JS
