推荐！Sublime Text 最佳插件列表
 
1.Package Control
2.EditorConfig
3.Emmet：html,css代码补全
4.SublimeLinter
	SublimeLinter-jshint -- JavaScript 语法检查
	SublimeLinter-csslint -- css语法检查
5.JSFormat  -- js 格式化
6.CSScomb   CSS属性排序
7.Tag 		html 标签
8.ColorPicker  --拾色器
9.sidebar     --右键open in broswer
10.Bracket Highlighter：匹配括号
11.Alignment：代码对齐
12.docblockr：生成注释插件[文档](https：//http://packagecontrol.io/packages/DocBlockr)
13.git：git
14.jQuery：jQuery
15.ConvertToUTF8：转码成utf-8，解决乱码
16.AutoPrefixer：用于CSS后处理，前端代码的话可能有Emmet就够了，这个主要是补上一些浏览器前缀神马的
17.FileDiffs：这个是用来比较文件差异的。手下的几个码农的代码风格与自己并不相同，经常代码汇总过来我都不知道他们改了什么，这个插件还是很给力的。

http://www.jianshu.com/p/712cea0ef70e
EditorConfig 介绍
 
SublimeLinter 是 Sublime 的插件，它的作用是检查代码语法是否有错误，并提示。
https://gaohaoyang.github.io/2015/03/26/sublimeLinter/
 
安装 SublimeLinter-jshint
https://github.com/SublimeLinter/SublimeLinter-jshint
 
JSFormat   JS格式化
CSScomb     CSS属性排序
 
语言高亮提示 jade 
Tag = Html格式化
 
MarkdownEditing
 
 
colorpicker
https://github.com/weslly/ColorPicker
 
	•	emmet：html,css代码补全
	•	sidebar：右键open in broswer
	•	Bracket Highlighter：匹配括号
	•	Sublime CodeIntel：代码补全```需要配置环境```
	•	Alignment：代码对齐
	•	docblockr：生成注释插件[文档](https：//http://packagecontrol.io/packages/DocBlockr)
	•	git：git
	•	jQuery：jQuery
	•	ConvertToUTF8：转码成utf-8，解决乱码
 
1.Package Control：这个是必须装的，就不多解释了
2.Emmet：原来的Zen Coding，功能太多，绝对神器，基本满足前端大部分代码习惯和强迫症需求
3.Alignment：等号对齐。这个是在做信安的时候发现的插件，用了PBC库以后基本所有代码都变成X=Y，有了这个插件代码要清晰地多
4.FileDiffs：这个是用来比较文件差异的。手下的几个码农的代码风格与自己并不相同，经常代码汇总过来我都不知道他们改了什么，这个插件还是很给力的。
5.JsFormat：Js代码格式化。用原生Js的朋友可能需要
6.AutoPrefixer：用于CSS后处理，前端代码的话可能有Emmet就够了，这个主要是补上一些浏览器前缀神马的
7.CSScomb：这个是CSS的属性排序用的，完全属于个人强迫症需求，不过代码规范化还是完全有必要的
 
 
http://blog.csdn.net/jinhui157/article/details/72887142
实用的sublime插件集合 – sublime推荐必备插件
 
http://blog.jobbole.com/79326/
推荐！Sublime Text 最佳插件列表


最佳的Sublime Text 插件

朋友们你们好！我尝试着收集了最佳的ST插件，这些插件真的会改善你的工作流程。我搜索了很多网站，下面是我的成果。

WebInspector

在 JavaScript调试方面，这是一个令人惊讶的工具，Sublime上的完整的代码检查工具。
功能：使用绝对路径储存在用户设置中的项目断点，控制台，分步和断点调试器，栈追踪。这些都能够很棒的工作！而且Mozilla还提供了一个插件Fireplay让你连接到Firefox 开发工具和最简单的调试器JSHint

视频

Emmet

编辑器中最流行的插件之一。Emmet，前身Zen Coding也是web开发者提高生产力最有效的方法之一。按下Tab键，Emmet就能把一个缩写展开成一个HTML和CSS代码块，我想提一下Hayaku-集合了方便的层叠样式表缩写。

包含最棒的技巧的视频，来自项目作者

Git

这个插件的实质，看一下它的名字就知道了–它提供了使用我们的最爱的编辑器直接和Git协同工作的机会。使用这种方式与Git协同工作会节省您大量的时间。首先：您不需要时常的在Sublime和终端间相互切换。另外：它具有tag自动补全功能，写add就足够了，而不是git add -A。第三点：它具有快速提交功能(quick)，一个命令添加所有变化并全部提交。

如果你只是想利用Git来获取远程仓库的内容，我推荐使用Nettuts+ Fetch.

有个叫Glue的插件，会在界面下方显示一个小窗口，你可以在那里写Shell脚本。这样一来，你的编辑器就不仅仅局限于使用Git了。

GitGutter & Modific

这些插件可以高亮相对于上次提交有所变动的行，换句话说是实时的diff工具。
1

BracketHighlighter

好极了！打开和折叠代码的某一部分就应该是这个样子的。
2

EditorConfig

3

EditorConfig帮助开发者在不同的编辑器，IDE之间定义和维护统一的编程风格。EditorConfig工程包含一个文件，定义了编程风格，文本编辑器插件集合，让编辑器可以读取该文件并依照它来定义风格。例如.editorconfig文件：


; html-script: false ]# top-most EditorConfig file
root = true

# Unix-style newlines with a newline ending every file
[*]
end_of_line = lf
insert_final_newline = true

# 4 space indentation
[*.py]
indent_style = space
indent_size = 4

# Tab indentation (no size specified)
[*.js]
indent_style = tab

# Indentation override for all JS under lib directory
[lib/**.js]
indent_style = space
indent_size = 2

# Matches the exact files either package.json or .travis.yml
[{package.json,.travis.yml}]
indent_style = space
indent_size = 2
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
; html-script: false ]# top-most EditorConfig file
root = true
 
# Unix-style newlines with a newline ending every file
[*]
end_of_line = lf
insert_final_newline = true
 
# 4 space indentation
[*.py]
indent_style = space
indent_size = 4
 
# Tab indentation (no size specified)
[*.js]
indent_style = tab
 
# Indentation override for all JS under lib directory
[lib/**.js]
indent_style = space
indent_size = 2
 
# Matches the exact files either package.json or .travis.yml
[{package.json,.travis.yml}]
indent_style = space
indent_size = 2
Sublimall

一个简洁的插件，可以让你在不同的Sublime Text 编辑器间同步所有的配置（设置，插件，打开的文件等等）所有的一切都是免费的，你只需要创建一个账户即可。是BufferScroll的一个更简约的替代品。

4

译者注：现在暂时无法注册
>Max registration reach
I’m sorry about that, don’t forget that it’s a beta version of Sublimall.
Registrations will been soon re-opened!
Geoffrey.

AllAutocomplete

传统的Sublime Text自动补全插件仅仅在当前文件下工作。AllAutocomplete 可以搜索全部打开的标签页，这将极大的简化开发进程。当然，还有一个插件叫 CodeIntel，实现了一些IDE的功能并且为一些语言提供了“代码情报”： JavaScript, Mason, XBL, XUL, RHTML, SCSS, Python, HTML, Ruby, Python3, XML, Sass, XSLT, Django, HTML5, Perl, CSS, Twig, Less, Smarty, Node.js, Tcl, TemplateToolkit, PHP.
5

SublimeREPL

对开发者来讲这个可能是最有用的插件之一了。SublimeREPL 可以直接在编辑器中运行一个解释器，支持很多语言：
Clojure, CoffeeScript, F#, Groovy, Haskell, Lua, MozRepl, NodeJS, Python, R, Ruby, Scala, shell
6

DocBlockr

DocBlockr会成为你编写代码文档的有效工具。当输入/**并且按下Tab键的时候，这个插件会自动解析任何一个函数并且为你准备好合适的模板
12

Floobits

7
SublimeText, Vim, Emacs, IntelliJ IDEA极佳的扩展工具，它使得开发者可以在从不同的编辑器合作编写代码。

AutoFileName

自动补全文件路径-非常方便。没有废话。
8

ColorPicker

通常，如果我们需要一个调色盘的时候，我们习惯使用Photoshop或是Gimp。但是一个完整的选色工具可以直接在你的编辑器中使用- Ctrl/Cmd + Shift + C。还有两个插件 GutterColor 和 ColorHighlightergutter可以在gutter中显示很棒的色彩高亮，简化了色彩代码的定位。
13

Colorcoder

高亮所有变量，因此可以极大的简化代码定位。尤其是对那些有阅读障碍的程序员非常有帮助。
9

PlainTasks

杰出的待办事项表！所有的任务都保持在文件中，所以可以很方便的把任务和项目绑定在一起。可以创建项目，贴标签，设置日期。有竞争力的用户界面和快捷键。
10

MarkdownEditing

可能是Markdonw最好的插件了：语法高亮，缩略词，自动补全，配色方案。你也可以尝试使用MarkdownPreview作为替代解决方案。
11

最后

Sublime SFTP
CTags – 让Sublime Text支持CTags.
SideBarEnhancement – 为侧边栏添加很多额外的功能.
ActualVim – Vim in Sublime – 两个最爱的编辑器合二为一.
SublimeLinter – 行内语法检测插件，支持： C/C++, Java, Python, PHP, JS, HTML, CSS, etc.
CSScomb – CSS代码风格格式化.
FixMyJS, Jsfmt and JsFormat – JS/JSON代码风格格式化.
AStyleFormatter – C/C++/C#/Java 代码风格格式化.
SVG-Snippets – 一套 SVG 代码片段.
Inc-Dec-Value – 增加或减少数字, 日期, 十六进制彩色值等等。
Trailing Spaces – 高亮空白结尾并快速删除它们
Alignment – Package Control作者写的简单到极致的多行选择和多行选择对齐插件
Placeholders – 带有文本，图片，列表，表格等的占位用代码片段
ApplySyntax – 快速语法检测
StylToken – 允许以不同的颜色高亮特定的一段文本 (类似和notepad++ 的Style token功能).
EasyMotion – 快速跳转到任何当前激活视图而已看到区域的字符
ZenTabs 和Advanced?New?File – 改进默认tab样式和文件创建.
EncodingHelper – 猜测文本的编码方式，在状态栏显示，从不同的编码形式转换到UTF-8
Gist – 同步GitHub Gist和Sublime (ST2).
Clipboard History (ST2) – 为的剪切板保存历史记录

主题和配色方案

Soda
Spacegray
Flatland
Tomorrow
Base 16
Solarized
Predawn
itg.flat
其他所有的配色方案和主题.
