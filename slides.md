---
# You can also start simply with 'default'
# theme: seriph
# theme: eloc
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background:
  # https://cover.sli.dev
  # some information about your slides (markdown enabled)

title: Welcome to Markdown
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true

# highlighter: shiki
---

# Welcome to Markdown

Markdown是一种广泛使用的轻量级标记语言

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    让我们开始吧 <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# **什么是Markdown？**

<center><img src="https://what_is_markdown.sikesibian.tech/image/slides/markdown_logo.png" /></center>
<br>
<center>上图是Markdown的Logo</center>

**Markdown 是一种轻量级的标记语言**，它允许人们**使用易读易写的纯文本格式编写文档**，然后**转换成有效的XHTML（或者HTML）文档**。Markdown 的核心目标之一是实现“易读易写”，即使在没有格式转换的情况下也能被阅读。 

说人话就是：**Markdown语法简单，好掌握，兼容性强，在哪儿都能用得到**。

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
p {
  font-size: 1.4em;
  line-height: 1.5;
}
</style>

---
layout: center
---

# 那么...

---
layout: center
---

# Markdown可以**干什么**？

---
layout: two-cols
layoutClass: gap-16
---

**下面就是一段Markdown代码** 

<div class="scroll">

````markdown

# 一个井号是一级标题

## 这是二级标题

这是一段正文内容

>也有引用。引文出处可以适当增加尾注[^1]

这是一段*歪斜的*或者**加粗的**或者***加粗倾斜的***正文内容

#### 1.1.1.1 也有多级标题

- 可以构建**列表**
- 也可以构建下面的**有序列表**

1. 当然有数学公式 $1^{2x + 8}\equiv 1$
2. 也有段内代码：`console.log('hello world')`

以及**大段代码**： 
```c
#include <stdio.h>
int main() {
  printf("Hello World");
  return 0;
}
```

还可以**引用图片**：

![](./image/slides/markdown_logo.png)

Markdown也支持html代码直接嵌入（这里**嵌入一个视频**）：

<iframe src="https://ugchsy.gtimg.com/B_JxNyiJmktHRgresXhfyMekuTffoV04LqjYvDrkOIY9piX1UjPAYkz6WuAF9z1wyF/svp_50069/gzc_1000035_0b535yakkaaasmai7kcppnqjl3wduxxabjka.f204110.mp4?sdtfrom=v1010&guid=4cafc5ab196598f4&vkey=E4DBCAE5C0181EA7E106162B80546B11C63CD42BED3F420972FA307BF2D9624FAE2D3786D0BD15A85174939B49C1566350917C07C53170B43B9D8531FFEA691141FFD0D375860FA65602A7A0FDECD5E4BE2D194AA0B9416336E27B289EB944497DE3FFDCAC8D760FB6F3DB2CE24D62A9BE3CB240DF23C1AB4E7179F0A066895DBE96079A871775D36ABF7D25C888E3C0AD079E36B0A851577BE95994ADCF6E473F92DF41035A0C0A" width="360" height="600" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

[^1]: 尾注 1 的内容。


````

</div>

::right::

**这是它被渲染后的样子：**

<div class="scroll">

# 一个井号是一级标题

## 这是二级标题

这是一段正文内容

>也有引用。引文出处可以适当增加尾注[^1]

这是一段*歪斜的*或者**加粗的**或者***加粗倾斜的***正文内容

#### 1.1.1.1 也有多级标题

- 可以构建**列表**
  - 和**多级列表**
- 也可以构建下面的**有序列表**

1. 当然有数学公式 $1^{2x + 8}\equiv 1$
2. 也有段内代码：`console.log('hello world')`

以及**大段代码**： 
```c
#include <stdio.h>
int main() {
  printf("Hello World");
  return 0;
}
```

还可以**引用图片**：

![](./image/slides/markdown_logo.png)

Markdown也支持html代码直接嵌入（这里**嵌入一个视频**）：

<iframe src="https://ugchsy.gtimg.com/B_JxNyiJmktHRgresXhfyMekuTffoV04LqjYvDrkOIY9piX1UjPAYkz6WuAF9z1wyF/svp_50069/gzc_1000035_0b535yakkaaasmai7kcppnqjl3wduxxabjka.f204110.mp4?sdtfrom=v1010&guid=4cafc5ab196598f4&vkey=E4DBCAE5C0181EA7E106162B80546B11C63CD42BED3F420972FA307BF2D9624FAE2D3786D0BD15A85174939B49C1566350917C07C53170B43B9D8531FFEA691141FFD0D375860FA65602A7A0FDECD5E4BE2D194AA0B9416336E27B289EB944497DE3FFDCAC8D760FB6F3DB2CE24D62A9BE3CB240DF23C1AB4E7179F0A066895DBE96079A871775D36ABF7D25C888E3C0AD079E36B0A851577BE95994ADCF6E473F92DF41035A0C0A" width="360" height="240" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

[^1]: 尾注 1 的内容。


</div>

<style>
  .slidev-layout {
    .scroll {
      @apply overflow-y-scroll max-w-5/5 max-h-[360px];

      p {
        @apply m-0;
      }
    }
  }
</style>


---
layout: center
---

# Markdown还可以**干什么**？


---

# Markdown可以**绘制表格**

|     |     |
| --- | --- |
| <kbd>right</kbd> / <kbd>space</kbd>| next animation or slide |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd> | previous slide |
| <kbd>down</kbd> | next slide |

<br>

注: **复杂表格的绘制往往需要使用html超文本标记语言**。

---

# 也可以**绘制图表**

<div class="grid grid-cols-4 gap-5 pt-4 -mb-6">

```mermaid {scale: 0.5, alt: 'A simple sequence diagram'}
sequenceDiagram
    Alice->John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

```mermaid {theme: 'neutral', scale: 0.8}
graph TD
B[Text] --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

```mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```

```plantuml {scale: 0.7}
@startuml

package "Some Group" {
  HTTP - [First Component]
  [Another Component]
}

node "Other Groups" {
  FTP - [Second Component]
  [First Component] --> FTP
}

cloud {
  [Example 1]
}

database "MySql" {
  folder "This is my folder" {
    [Folder 3]
  }
  frame "Foo" {
    [Frame 4]
  }
}

[Another Component] --> [Example 1]
[Example 1] --> [Folder 3]
[Folder 3] --> [Frame 4]

@enduml
```

</div>

<br>
<br>
<br>

注: 这里使用的是文本绘图工具 **Mermaid** 和 **PlantUML**

---

# Markdown可以**制作博客**

<iframe src="https://ucas-ctf.github.io/" width="100%" height="600" frameborder="0"></iframe>


---
layout: center
---

# 对了

---
layout: center
---

# 这个**PPT**也是基于Markdown完成的

---

# **Markdown的学习资源**：

- [**Markdown 语法参考**](https://www.markdown.cn/docs/tutorial-basics/basic-syntax): https://www.markdown.cn/docs/tutorial-basics/basic-syntax
- [**在VSCode中使用Markdown**](https://blog.csdn.net/un357951/article/details/110927171): https://blog.csdn.net/un357951/article/details/110927171

- **相关重要工具** ：
  - **Pandoc** ：一个强大的命令行工具，用于文件格式转换，特别是Markdown文件。支持数十种文件格式的转换，包括Markdown、HTML、Docx、PDF等。Pandoc不仅支持基础的文档转换，还支持通过Lua、Python等脚本语言实现高度自定义的文档转换。  
  - **simpletex** ：在线图片转公式识别网站（https://simpletex.cn/ai/latex_ocr ）  

- **相关非交互式笔记工具** ：  
  - **Obsidian** ：一个**离线**支持Markdown的笔记管理工具，支持Markdown语法的笔记编辑，支持插件扩展。  
  - **Typora** ：一款**离线**简洁高效的跨平台Markdown编辑器，支持实时预览，让用户在编辑文本的同时可以立即看到格式化后的效果，可在Windows、macOS和Linux系统上运行。  
  - **语雀** ：一个**在线**知识管理工具，支持Markdown格式的文档，也支持直接导出PDF、Markdown等格式，可以自动生成PPT。  
---

# **Markdown相关应用**：

- **相关博客工具** ：
  - **Hexo** ：一个快速、简洁且高效的博客框架，支持Markdown、Nunjucks等模板引擎，支持插件扩展。  
  - **Hugo** ：一个静态网站生成器，支持Markdown、HTML等格式的文档，支持插件扩展。  
  - **GitHub Pages** ：一个免费托管静态网站、博客、文档等资源的平台，支持Markdown、HTML等格式的文档。
- **相关在线互动型PPT制作工具** ： 
  - **Slidev** ：一个基于Vue的Markdown驱动的PPT工具，支持Markdown语法，支持插件扩展。更多功能支持需要开发者有较好的Typescript和HTML/CSS等前端知识。  
- **交互式或非交互式笔记工具** ：
  - **Jupyter Notebook** ：一个交互式计算环境，支持Markdown、Python等编程语言，支持插件扩展。  
  - **Emacs Org-Mode** ：一个Emacs插件，支持Markdown、Org-Mode等格式的笔记，支持插件扩展。  


---
layout: two-cols
layoutClass: gap-16
---

<Toc minDepth="1"></Toc>

::right::

<br>
<br>
<br>
<br>
<br>
<br>
<br>

# **谢谢！**
