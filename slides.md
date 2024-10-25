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
transition: slide-up
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

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---

# **什么是Markdown？**

<center><img src="./image/slides/markdown_logo.png" /></center>
<br>
<center>上图是Markdown的Logo</center>

**Markdown 是一种轻量级的标记语言**，它允许人们**使用易读易写的纯文本格式编写文档**，然后**转换成有效的XHTML（或者HTML）文档**。Markdown 的核心目标之一是实现“易读易写”，即使在没有格式转换的情况下也能被阅读。 

说人话就是：**Markdown语法简单，好掌握，兼容性强，在哪儿都能用得到**。

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

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


<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
layout: center
transition: slide-left
---

# Markdown可以**干什么**？

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
layout: two-cols
layoutClass: gap-16
transition: slide-up
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

<iframe src="https://player.bilibili.com/player.html?isOutside=true&aid=812371035&bvid=BV1g34y1j7e5&cid=739670424&p=1"  width="360" height="240"  scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

[^1]: 尾注 1 的内容。


````

</div>

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
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

<iframe src="https://player.bilibili.com/player.html?isOutside=true&aid=812371035&bvid=BV1g34y1j7e5&cid=739670424&p=1"  width="360" height="240"  scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

[^1]: 尾注 1 的内容。


</div>

<style>
  .slidev-layout {
    .scroll {
      @apply overflow-y-scroll max-w-5/5 max-h-[340px];

      p {
        @apply m-0;
      }
    }
  }
</style>


---
layout: center
transition: slide-left
---

## Markdown**还**可以**干什么**？

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
transition: slide-left
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


<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
transition: slide-left
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

注: 这里使用的是文本绘图工具 **Mermaid** 和 **PlantUML**

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
transition: slide-left
---

# Markdown可以**制作博客**

<iframe src="https://ucas-ctf.github.io/" width="100%" height="360" frameborder="0"></iframe>

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
layout: center
---

# 对了

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
layout: center
---

# 这个**PPT**

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
layout: center
transition: slide-right
---

# 也是基于Markdown完成的😎

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

---
transition: slide-left
---

<div class="chat">

  <p class="left">Markdown能<b>支持这么多格式、内容</b></p>

  <p v-click class="left"><b>那我应该到哪里去学习Markdown呢？</b></p>

  <p v-click> 别急，我<b>马上向您介绍！</b> </p>

</div>

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

<style>
  .slidev-layout {
    h2 {
      @apply mb-9;
    }

    .chat {
      @apply w-full max-h-[660px] pb-[100px];
      @apply flex flex-col justify-start;

      p {
        @apply relative self-end m-6 px-5 py-3; 
        @apply rounded-[32px] bg-[#eee];
        font-size: 24px;

        &.left {
          @apply self-start;
        }

        &::before {
          content: '';
          @apply absolute top-2 -left-3 w-5 h-8;
          @apply border-b-[16px] border-solid border-[#eee] rounded-bl-full;
        }

        &:not(.left)::before {
          left: unset;
          @apply -right-4 rounded-none rounded-br-full;
        }
      }
    }
  }
</style>


---
transition: slide-right
---

# **Markdown的学习资源**：

- [**Markdown 语法参考**](https://www.markdown.cn/docs/tutorial-basics/basic-syntax): https://www.markdown.cn/docs/tutorial-basics/basic-syntax
- [**在VSCode中使用Markdown**](https://blog.csdn.net/un357951/article/details/110927171): https://blog.csdn.net/un357951/article/details/110927171

<v-clicks depth="1">

- **相关重要工具** ：
  - **Pandoc** ：一个强大的命令行工具，用于文件格式转换，特别是Markdown文件。支持数十种文件格式的转换，包括Markdown、HTML、Docx、PDF等。
  - **simpletex** ：在线图片转公式识别网站（https://simpletex.cn/ai/latex_ocr ）  

- **相关非交互式笔记工具** ：  
  - **Obsidian** ：一个**离线**支持Markdown的笔记管理工具，支持Markdown语法的笔记编辑，支持插件扩展。  
  - **Typora** ：一款**离线**简洁高效的跨平台Markdown编辑器，支持实时预览，让用户在编辑文本的同时可以立即看到格式化后的效果，可在Windows、macOS和Linux系统上运行。  
  - **语雀** ：一个**在线**知识管理工具，支持Markdown格式的文档，也支持直接导出PDF、Markdown等格式，可以自动生成PPT。  

</v-clicks>

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

<style>
  .slidev-vclick-target {
      transition: all 500ms ease;
  }
  .slidev-vclick-hidden {
      transform: scale(0);
  }
</style>

---
transition: slide-left
---

<div class="chat">

  <p class="left">Markdown能<b>支持这么多格式、内容</b></p>

  <p class="left"><b>那我应该到哪里去学习Markdown呢？</b></p>

  <p> 别急，我<b>马上向您介绍！</b> </p>

  <p> 除此之外，Markdown还<b>在很多其他地方有广泛应用</b> </p>

</div>

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

<style>
  .slidev-layout {
    h2 {
      @apply mb-9;
    }

    .chat {
      @apply w-full max-h-[660px] pb-[100px];
      @apply flex flex-col justify-start;

      p {
        @apply relative self-end m-6 px-5 py-3; 
        @apply rounded-[32px] bg-[#eee];
        font-size: 24px;

        &.left {
          @apply self-start;
        }

        &::before {
          content: '';
          @apply absolute top-2 -left-3 w-5 h-8;
          @apply border-b-[16px] border-solid border-[#eee] rounded-bl-full;
        }

        &:not(.left)::before {
          left: unset;
          @apply -right-4 rounded-none rounded-br-full;
        }
      }
    }
  }
</style>


---
transition: slide-left
---

# **Markdown相关应用**：

- **相关博客工具** ：
  - **Hexo** ：一个基于 Node.js 的静态博客生成器，以其易用性和丰富的插件生态而受到欢迎，特别适合需要快速搭建博客的用户。  
  - **Hugo** ：一个用 Go 语言编写的高性能静态网站生成器，以其快速的构建速度和灵活的模板系统著称，适合追求速度和性能的用户。  
  - **GitHub Pages** ：一个由 GitHub 提供的免费静态网站托管服务，支持直接从仓库部署网站，非常适合个人、项目文档和小团队的静态网站托管需求。支持 Jekyll 作为默认的静态网站生成器，但也可以通过其他工具生成静态网页后上传。  
  - **Jekyll** ：一个用 Ruby 编写的静态网站生成器，以其简洁的模板系统和与 GitHub Pages 的无缝集成而受到喜爱，特别适合那些喜欢在 GitHub 上托管和维护静态网站的用户。  


<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

<style>
  .slidev-vclick-target {
      transition: all 500ms ease;
  }
  .slidev-vclick-hidden {
      transform: scale(0);
  }
</style>

---
transition: slide-up
---

- **相关在线互动型PPT制作工具** ： 
  - **Slidev** ：一个为开发者设计的现代化、基于 Web 的幻灯片制作和演示工具，它**允许用户使用 Markdown 语法**来创建内容丰富的幻灯片，同时**结合了 HTML 和 Vue.js 组件的强大功能**。这使得开发者能够以编写代码的方式轻松构建美观且互动性强的演示文稿。（不过PPT制作还是建议使用 Office PowerPoint 或者 Beamer）  

<v-clicks depth="1">

- **交互式笔记工具** ：
  - **Jupyter Notebook** ：是一个交互式的Web应用程序，用于创建和分享包含代码、数学方程、可视化和文本的文档。它支持多种编程语言，特别适合数据科学和机器学习，允许用户在浏览器中进行编码和数据分析。**它允许用户在浏览器中编写代码、运行代码、查看输出、可视化数据并查看结果**，非常适合进行交互式数据分析和探索性编程。
  - **Emacs** ：是一个高度可定制的文本编辑器，由Richard Stallman创建，是自由软件运动的一部分。但 Emacs 并不局限于编辑器，而且是**一个功能丰富的开发环境，支持多种编程语言的编辑、调试和版本控制**，使用自己的 **Lisp 方言（Emacs Lisp）** 来扩展和定制。它的设计理念是“一个就够了”，你可以用它来**编写代码、管理邮件、浏览网页、玩游戏，甚至可以用来煮咖啡**。Emacs 的学习曲线可能比较陡峭，但是一旦熟练掌握，它将成为一个强大的生产力工具。  

</v-clicks>

<div class="absolute bottom-10 opacity-50" style="left: 0; right: 0; padding: 0 40px;">
<SlideCurrentNo />/<SlidesTotal />
</div>

<style>
  .slidev-vclick-target {
      transition: all 500ms ease;
  }
  .slidev-vclick-hidden {
      transform: scale(0);
  }
</style>

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

<div class="absolute bottom-10 opacity-50">
<SlideCurrentNo />/<SlidesTotal />
</div>
