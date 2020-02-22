<html>
<!--注释：背景颜色设置<body style="background-color:PowderBlue">-->

<!--设置全局标题颜色/对HTML进行格式化-->
<head>
<style type="test/css">
h2{color:read}
h3{color:blue}
</style>
</head>

<h1 style="text-align:center">HTML学习</h1>
来源：<a href="http://www.w3school.com.cn">w3school</a>

<h2>HTML简介</h2>

<h3>什么是HTML</h3>

<p>HTML是用来描述网页的一种语言。
HTML指的是超文本标记语言（Hyper Text Markup Language）
HTML不是一种编程语言，二是一种标记语言（markup language）
标记语言是一套标记标签（markup tag）
HTML使用标记标签来描述网页</p>

<h3>HTML标签</h3>

<p>HTML 标记标签通常被称为 HTML 标签 (HTML tag)。
HTML 标签是由尖括号包围的关键词，比如由尖括号包围的“html”
HTML 标签通常是成对出现的，比如 <b> 和 </b>
标签对中的第一个标签是开始标签，第二个标签是结束标签
开始和结束标签也被称为开放标签和闭合标签</p>

<h3>HTML 文档 = 网页</h3>

<p>HTML 文档描述网页
HTML 文档包含 HTML 标签和纯文本
HTML 文档也被称为网页
Web 浏览器的作用是读取 HTML 文档，并以网页的形式显示出它们。浏览器不会显示 HTML 标签，而是使用标签来解释页面的内容：</p>

<h3>例子解释</h3>
省略...

<h2>HTML编辑器</h2>
省略...

<h2>HTML基础</h2>

<h3>HTML链接</h3>

HTML 链接是通过 <a> 标签进行定义的。
注释：在href属性中制定链接的地址。
实例
<a href="http://www.w3school.com.cn">This is a link</a>

<h3>HTML图像</h3>

HTML图像是通过<img>标签进行定义的。
实例
<img src="pigup.gif" width="104" height="104" >

<h2>HTML元素</h2>

<h3>HTML元素</h3>

<p>HTML文档是由HTML元素定义的。
HTML 元素指的是从开始标签（start tag）到结束标签（end tag）的所有代码。
注释：开始标签常被称为开放标签（opening tag），结束标签常称为闭合标签（closing tag）。</p>

<h3>HTML元素语法</h3>

<p>HTML 元素以开始标签起始
HTML 元素以结束标签终止
元素的内容是开始标签与结束标签之间的内容
某些 HTML 元素具有空内容（empty content）
空元素在开始标签中进行关闭（以开始标签的结束而结束）
大多数 HTML 元素可拥有属性</p>


<h3>嵌套的HTML元素</h3>
<p>
大多数 HTML 元素可以嵌套（可以包含其他 HTML 元素）。
HTML 文档由嵌套的 HTML 元素构成。
<p> 元素定义了 HTML 文档中的一个段落。
<body> 元素定义了 HTML 文档的主体。
<html> 元素定义了整个 HTML 文档。</p>

<h3>不要忘记结束标签</h3>

<p>即使您忘记了使用结束标签，大多数浏览器也会正确地显示 HTML：
在大多数浏览器中都没问题，但不要依赖这种做法。忘记使用结束标签会产生不可预料的结果或错误。
注释：未来的 HTML 版本不允许省略结束标签。</p>

<h3>空的 HTML 元素</h3>

<p>没有内容的 HTML 元素被称为空元素。空元素是在开始标签中关闭的。

<br> 就是没有关闭标签的空元素（<br> 标签定义换行）。

在 XHTML、XML 以及未来版本的 HTML 中，所有元素都必须被关闭。

在开始标签中添加斜杠，比如 <br />，是关闭空元素的正确方法，HTML、XHTML 和 XML 都接受这种方式。

即使 <br> 在所有浏览器中都是有效的，但使用 <br /> 其实是更长远的保障。</p>

<h3>HTML提示：使用小写标签</h3>
<p>
HTML 标签对大小写不敏感：<P> 等同于 <p>。许多网站都使用大写的 HTML 标签。
W3School 使用的是小写标签，因为万维网联盟（W3C）在 HTML 4 中推荐使用小写，而在未来 (X)HTML 版本中强制使用小写。</p>

<h2>HTML属性</h2>

<h3>HTML属性</h3>

<p>
属性为HTML元素提供附加信息。
HTML 标签可以拥有属性。属性提供了有关 HTML 元素的更多的信息。
属性总是以名称/值对的形式出现，比如：name="value"。
属性总是在 HTML 元素的开始标签中规定。
</p>

<h3>属性实例</h3>

<p>HTML 链接由 <a> 标签定义。链接的地址在 href 属性中指定：
<a href="http://www.w3school.com.cn">This is a link</a>
</p>

<h3>更多HTML属性实例</h3>

<h4>属性例子 1：</h4>
<p>
省略....
</p>

<h4>属性例子 2：</h4>
<p>
body 定义 HTML 文档的主体。
body bgcolor="某种颜色" 拥有关于背景颜色的附加信息。
</p>

<h4>属性例子 3：</h4>
<p>
<table> 定义 HTML 表格。（您将在稍后的章节学习到更多有关 HTML 表格的内容）
<table border="1"> 拥有关于表格边框的附加信息。
</p>

<h3>HTML提示：使用小写属性</h3>

<p>
属性和属性值对大小写不敏感。
不过，万维网联盟在其 HTML 4 推荐标准中推荐小写的属性/属性值。
而新版本的 (X)HTML 要求使用小写属性。
</p>

<h3>始终为属性值加引号</h3>
<p>
属性值应该始终被包括在引号内。双引号是最常用的，不过使用单引号也没有问题。
在某些个别的情况下，比如属性值本身就含有双引号，那么您必须使用单引号，
例如：
name='Bill "HelloWorld" Gates'
</p>

<h3>HTML属性参考手册</h3>
<p>
属性              值                        描述
class       classname          规定元素的类名（classname）
id                  id                规定元素的唯一 id
style       style_definition   规定元素的行内样式（inline style）
title              text              规定元素的额外信息（可在工具提示中显示） 
</p>

<h2>HTML标题</h2>

<h3>HTML标题</h3>

<p>
标题（Heading）是通过h1-h6等标签进行定义的。
标签大小依次递减
注释1：浏览器会自动地在标题的前后添加空行。
注释2：默认情况下，HTML 会自动地在块级元素前后添加一个额外的空行，比如段落、标题元素前后。
</p>

<h3>标题很重要</h3>

<p>
请确保将 HTML heading 标签只用于标题。不要仅仅是为了产生粗体或大号的文本而使用标题。
搜索引擎使用标题为您的网页的结构和内容编制索引。
因为用户可以通过标题来快速浏览您的网页，所以用标题来呈现文档结构是很重要的。
应该将 h1 用作主标题（最重要的），其后是 h2（次重要的），再其次是 h3，以此类推。
</p>

<h3>HTML水平线</h3>

<p> hr 标签定义水平线</p>
<hr />
<p>This is a paragraph</p>
<hr />
<p>提示：使用水平线 (<hr> 标签) 来分隔文章中的小节是一个办法（但并不是唯一的办法）。</p>

<h3>HTML注释</h3>

<p>可以将注释插入 HTML 代码中，这样可以提高其可读性，使代码更易被人理解。浏览器会忽略注释，也不会显示它们。
注释是这样写的：
实例 ：<!-- This is a comment -->小心，这里会隐藏
注释：开始括号之后（左边的括号）需要紧跟一个叹号，结束括号之前（右边的括号）不需要。
提示：合理地使用注释可以对未来的代码编辑工作产生帮助。</p>

<h3>HTML提示-如何查看源代码</h3>

<p>
只需要单击右键，然后选择“查看源文件”（IE）或“查看页面源代码”（Firefox），其他浏览器的做法也是类似的。这么做会打开一个包含页面 HTML 代码的窗口。
</p>

<h2>HTML段落</h2>

<h3>HTML段落</h3>

<p>
段落是通过 p 标签定义的。
<br/>
<b>实例</b>
<p>This is a paragraph</p>
<p>This is another paragraph</p>
注释：浏览器会自动地在段落的前后添加空行。（<p> 是块级元素）
提示：使用空的段落标记 <p></p> 去插入一个空行是个坏习惯。用后边这个标签代替它<br />！
</p>

<h3>HTML折行</h3>

如果您希望在不产生一个新段落的情况下进行换行（新行），请使用 "br/"
<p>This is<br />a para<br />graph with line breaks</p>
 "br/" ：折行元素是一个空的 HTML 元素。由于关闭标签没有任何意义，因此它没有结束标签。<br/>
"br" 还是 "br/"
您也许发现 方括号中br后一个有“/”一个没有。
在 XHTML、XML 以及未来的 HTML 版本中，不允许使用没有结束标签（闭合标签）的 HTML 元素。
即使br后没有“/”在所有浏览器中的显示都没有问题，br后带“/”也是更长远的保障。
</p>

<h3 style="font-family:verdana">HTML输出-有用的提示</h3>
<p>
我们无法确定 HTML 被显示的确切效果。屏幕的大小，以及对窗口的调整都可能导致不同的结果。
对于 HTML，您无法通过在 HTML 代码中添加额外的空格或换行来改变输出的效果。
当显示页面时，浏览器会移除源代码中多余的空格和空行。所有连续的空格或空行都会被算作一个空格。<br/>需要注意的是，HTML 代码中的所有连续的空行（换行）也被显示为一个空格。
</p>

<h2>HTML样式</h2>

<h3>HTML的style属性</h3>

<p style="font-family:Verdana;color:red">This text is in Verdana and red</p>
<p style="font-family:times;color:blue">This text is in Times and blue</p>
<p style="font-size:20p">This text is 20 pixels high</p>

<h2>HTML文本格式化</h2>

<h3 >HTML文本格式实例</h3>

<h4 >文本格式化</h4>
<p>此例演示如何在一个 HTML 文件中对文本进行格式化</p>
<b>This text is bold</b>
<br/> <! --换行-->
<strong>This text is strong</strong>
<br/>
<big>This text is big</big>
<br/>
<em>This text is emphasized</em>
<br/>
<i>This text is italic</i>
<br/>
<small>This text is small</small>
<br/>
This text contains
<sub>subscript</sub>
<br/>
This text contains
<sup>superscript</sup>

<h3 >预格式文本</h3>

<p>此例演示如何使用 pre 标签对空行和空格进行控制。</p>
<pre>
这是预格式文本。
它保留了      空格
和换行。
</pre>
<p>pre 标签很适合显示计算机代码：</p>
<pre>
for i = 1 to 10
      print i
next i
</pre>

<h3 >"计算机输出"标签</h3>

<p>此例演示不同的“计算机输出”标签的显示效果</p>
<code>Computer code</code>
<br/><! --换行-->
<kbd>Keyboard input</kbd>
<br/>
<tt>Teletype text</tt>
<br/>
<samp>Sample text</samp>
<br/>
<var>Comeputer variable</var>
<p><b>注释：</b>这些标签常用于显示计算机/编程代码。</p>

<h3 >地址</h3>

<p>此例演示如何在HTML文件中写地址。</p>
<address>
Written by <a href="mailto:DoubleHok@163.com">我的邮箱</a>.<br/>
Visit us at:<br/>
Example.com<br/>
Box 564,Disneyland<br/>
CHINA
</address>

<h3 >缩写和首字母缩写</h3>

<p>此例演示如何实现缩写或首字母缩写</p>
<abbr title="etcetera">etc.</abbr>
<br />
<acronym title="World Wide Web">WWW</acronym>
<p>在某些浏览器中，当您把鼠标移至缩略词语上时，title 可用于展示表达的完整版本。</p>
<p>仅对于 IE 5 中的 acronym 元素有效。</p>
<p>对于 Netscape 6.2 中的 abbr 和 acronym 元素都有效。</p>

<h3>块引用</h3>

<p>此例演示如何实现长短不一的引用语</p>
这是长引用：
<blockquote>
这是长引用。这是长引用。这是长引用。这是长引用。这是长引用。这是长引用。这是长引用。这是长引用。
这是长引用。这是长引用。这是长引用。这是长引用。这是长引用。这是长引用。
</blockquote>
这是短的引用：
<q>
这是短的引用。
</q>
<p>
使用blockquote元素的话，浏览器会插入换行和外边距，而q元素不会有任何特殊的呈现。
</p>

<h3>删除字效果和插入字效果</h3>

<p>此例演示如何标记删除文本和插入文本</p>
<p>一打有<del>二十</del> <ins>十二</ins> 件。</p>
<p>大多数浏览器会改写为删除文本和下划线文本。</p>
<p>一些老式的浏览器会吧删除文本和下划线文本显示文普通文本。</p>

<h3 >文本格式化标签</h3>
<p>
标签	描述
b	定义粗体文本。
big	定义大号字。
em	定义着重文字。
i	定义斜体字。
small	定义小号字。
strong	定义加重语气。
sub	定义下标字。
sup	定义上标字。
s	不赞成使用。使用 del 代替。
strike	不赞成使用。使用 del 代替。
u	不赞成使用。使用样式（style）代替。
</p>

<h3 >“计算机输出”标签</h3>

<p>
标签	描述
code	定义计算机代码。
kbd	定义键盘码。
samp	定义计算机代码样本。
tt	定义打字机代码。
var	定义变量。
pre	定义预格式文本。
listing	不赞成使用。使用 pre 代替。
plaintext	不赞成使用。使用  pre代替。
xmp	不赞成使用。使用  pre代替。
</p>

<h3 >引用、引用和术语定义</h3>
<p>
标签	描述
abbr	定义缩写。
acronym	定义首字母缩写。
address    定义地址。
bdo	定义文字方向。
blockquote	定义长的引用。
q	定义短的引用语。
cite	定义引用、引证。
dfn	定义一个定义项目。
</p>

<a herf="/HTML学习/HTML教程延伸阅读：改变文本的外观和含义.html" target="_blank">HTML教程延伸阅读：改变文本的外观和含义</a>

<h2>HTML引用</h2>

<h3>引用（Quotation）</h3>

<p>这是摘自 WWF 网站的引文：<br/>

五十年来，WWF 一直致力于保护自然界的未来。 世界领先的环保组织，WWF 工作于 100 个国家，<br/>
并得到美国一百二十万会员及全球近五百万会员的支持。</p>

<h3>HTML“q”用于短的引用</h3>

<p>浏览器通常“q”为元素包围引号</p>
<b>实例</b>
<p>WWF 的目标是：“q”构建人与自然和谐共存的世界。</q></p>

<h3>用于长引用的HTML"blockquote"</h3>
<p>浏览器通常会对"blockquote"元素进行缩进处理</p>
<big>实例</big>
<p>以下内容引用自 WWF 的网站：</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
五十年来，WWF 一直致力于保护自然界的未来。
世界领先的环保组织，WWF 工作于 100 个国家，
并得到美国一百二十万会员及全球近五百万会员的支持。
</blockquote>

<h3>用于缩略词的HTML"abbr"</h3>
<p>"abbr"定义缩写或首字母缩略词<br/>
对缩写进行标记能够为浏览器、翻译系统以及搜索引擎提供有用的信息
</p>
<strong>实例</strong>
<p><abbr title="World Health Organization">WHO</abbr>成立于1948年。</p>

<h3>用于定义的HTML"dfn"</h3>

<p>"dfn"定义项目或缩写的定义</p>
1.如果 设置了<dfn>元素的title属性，则定义项目：
<i>实例</i>
<p>The <dfn title="World Health Organization">WHO</dfn> was founded in 1948.</p>
<p>对缩写进行标记能够为浏览器、翻译系统以及搜索引擎提供有用的信息。</p>
2.如果"dfn"元素包含具有标题的"abbr元素，则title定义项目：
<em>实例</em>
<p>The
<dfn><abbr title="World Health Organization">WHO</abbr></dfn>
was founded in 1948.
</p>
<p>对缩写进行标记能够为浏览器、翻译系统以及搜索引擎提供有用的信息。</p>
3.否则，"dfn"文本内容即是项目，并且父元素包含定义。
<small>实例</small>
<p><dfn>WHO</dfn>World Health Organization 成立于1984年。</p>
<b>注释：</b>如果您希望简而化之，请使用第一条，或者使用"abbr"代替

<h3>用于联系信息的HTML"address"</h3>
<p>定义文档或文章的联系信息（作者|拥有者）</p>
<b>实例</b>
<p>HTML address 元素定义文档或文章的联系信息（作者/拥有者）。</p>

<address>
Written by Jon Doe.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

<h3>用于著作标题的HTML"cite"</h3>
<p>定义著作的标题。
浏览器通常会以斜体显示"cite"元素。</p>
<b>实例</b>
<p>HTML cite 元素定义著作的标题。</p>
<p>浏览器通常会以斜体显示 cite 元素。</p>

<img src="flower.gif" width="170" height="177" alt="The Scream" style="margin-left:40px">
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>

<h3>用户双向重写的HTML"bdo"</h3>
<p>定义双流向覆盖（bi-directional override）
“bdo”元素用于覆盖当前文本方向</p>
<b>实例</b>
<p>
如果您的浏览器支持 bdo，则文本将从右向左进行书写 (rtl)：
</p>
<bdo dir="rtl">
This line will be written from right to left
</bdo>
<h3>HTML引文、引用和定义元素</h3>
<p><pre>
标签	描述
abbr	定义缩写或首字母缩略语。
address	定义文档作者或拥有者的联系信息。
bdo	定义文本方向。
blockquote	定义从其他来源引用的节。
dfn	定义项目或缩略词的定义。
q	定义短的行内引用。
cite	定义著作的标题。
</pre></p>

<h2>HTML计算机代码元素</h2>

<h3>HTML计算机代码格式</h3>

<p>通常，HTML 使用可变的字母尺寸，以及可变的字母间距。<br/>
在显示计算机代码示例时，并不需要如此。<br/>
kbd, samp, 以及 code 元素全都支持固定的字母尺寸和间距。</p>

<h3>HTML键盘格式</h3>

HTML"kbd"元素定义键盘输入
<br/>
<b>实例</b>
<br/>
<p>HTML kbd 元素表示键盘输入：</p>
<p><kbd>File | Open...</kbd></p>

<h3>HTML样式格式</h3>
HTML samp元素定义计算机输出示例
<br/>
<b>实例</b>
<br/>
<samp>
demo.example.com login: Apr 12 09:10:17<br/>
Linux 2.6.10-grsec+gg3+e+fhs6b+nfs+gr0501+++p3+c4a+gr2b-reslog-v6.189
</samp>

<h3>HTML代码格式</h3>
HTML code元素定义变成代码示例
<br/>
<b>实例</b>
<br/>
<code>
var person = {firstName:"Bill", lastName:"Gats", age:50}
</code><br/>
code元素不保留多余的空格和折行：
<br/>
<b>实例</b>
<br/>

<code>
var person = {
    firstName:"Bill",
    lastName:"Gates",
    age:50,
    eyeColor:"blue"
}
</code>
如需解决该问题，您必须在pre元素中包围代码:
<br/>
<b>实例</b>
<br/>

<code>
<pre>
var person = {
    firstName:"Bill",
    lastName:"Gates",
    age:50,
    eyeColor:"blue"
}
</pre>
</code>

<h3>HTML变量格式化</h3>
HTML var元素定义数学变量：
<br/>
<b>实例</b>
<br/>
<p>爱因斯坦的公式：</p>
<p><var>E</var>=<var>m</var><var>c</var><sup>2</sup></p>

<h3>HTML计算机代码元素</h3>
<p><pre>
标签	描述
code	定义计算机代码文本
kbd	定义键盘文本
samp	定义计算机代码示例
var	定义变量
pre	定义预格式化文本
</pre></p>

<h3>没有下划线的链接</h3>
本例演示如何使用样式属性做一个没有下划线的链接
<br/>
<b>实例</b>
<br/>

<head>
<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
<meta http-equiv="Content-Language" content="zh-cn" />
</head>

<a href="/example/html/lastpage.html" style="text-decoration:none">
这是一个链接！
</a>

<h3>链接到一个外部样式表</h3>
本例演示如何使用link标签链接到一个外部样式表
<br/>
<b>实例</b>
<br/>

<head>
<link rel="stylesheet" type="text/css" href="/html/csstest1.css" >
</head>

<body>
<h1>我通过外部样式表进行格式化。</h1>
<p>我也一样！</p>
</body>

<h3>如何使用样式</h3>

当浏览器读到一个样式表，它就会按照这个样式表来对文档进行格式化。
<br/>
有以下三种方式来插入样式表：

<h4>外部样式表</h4>
当样式需要被应用到很多页面的时候，外部样式表将是理想的选择。
<br/>
使用外部样式表，你就可以通过更改一个文件来改变整个站点的外观。
<br/>
<b>实例</b>
<br/>

<head>
<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>

<h4>内部样式表</h4>
当单个文件需要特别样式时，就可以使用内部样式表。你可以在 head 部分通过 <style> 标签定义内部样式表。
<br/>
<b>实例</b>
<br/>

<head>
<style type="text/css">
body {background-color: red}
p {margin-left: 20px}
</style>
</head>

<h4>内联样式</h4>
当特殊的样式需要应用到个别元素时，就可以使用内联样式。 使用内联样式<br/>
的方法是在相关的标签中使用样式属性。样式属性可以包含任何 CSS 属性。<br/>
以下实例显示出如何改变段落的颜色和左外边距。
<br/>
<b>实例</b>
<br/>

<p style="color: red; margin-left: 20px">
This is a paragraph
</p>

<h3>HTML css</h3>

<p><pre>
标签	描述
style	定义样式定义。
link	定义资源引用。
div	定义文档中的节或区域（块级）。
span	定义文档中的行内的小块或区域。
font	规定文本的字体、字体尺寸、字体颜色。不赞成使用。请使用样式。
basefont	定义基准字体。不赞成使用。请使用样式。
center	对文本进行水平居中。不赞成使用。请使用样式。
</pre></p>

<h2>HTML链接</h2>
HTML 使用超级链接与网络上的另一个文档相连。
<br/>
几乎可以在所有的网页中找到链接。点击链接可以从一张页面跳转到另一张页面。

<h3>创建超级链接</h3>

本例演示如何在HTML文档中创建链接
<br/>
<b>实例</b>
<br/>

<p>
<a href="http://www.baidu.com">百度</a> 是一个指向百度的一个页面的链接。</p>
<p><a href="http://www.360doc.com/content/19/0615/15/5333684_842614739.shtml" target="_blank">GIF动态LOGO设计欣赏</a> 是一个指向gif动态logo涉及欣赏页面的链接。</p>

<h3>将图像作为链接</h3>
本例演示如何使用图像作为链接
<br/>
<b>实例</b>
<br/>

<p>
您也可以使用图像来作链接：
<br/>
<a href="/lastpage.html/">
<img border="0" src="/buttonnext.gif" />
</a>
</p>

<h3>HTML超链接</h3>

超链接可以使一个字，一个词，或者一组词，也可以是一幅图像，您可以点击这些内容来跳转到新的文档或者当前文档中的某个部分。<br/>
当您把鼠标指针移动到网页中的某个链接上时，箭头会变为一只小手。
<br/>
我们通过使用 <a> 标签在 HTML 中创建链接。
有两种使用 <a> 标签的方式：
1.通过使用 href 属性 - 创建指向另一个文档的链接
2.通过使用 name 属性 - 创建文档内的书签
<p><b>延伸阅读：</b><a href="/什么是超文本.html" target="_blank">什么是超文本</a></p>

<h3>HTML链接-target属性</h3>

<p>使用Target属性，你可以定义被链接的文档在何处显示。</p>
下面的这行会在新窗口打开文档：<br/>

<a href="http://www.w3school.com.cn/" target="_blank">Visit W3School!</a>

<h3>HTML链接-name属性</h3>
<p>
name 属性规定锚（anchor）的名称。<br/>

您可以使用 name 属性创建 HTML 页面中的书签。<br/>

书签不会以任何特殊方式显示，它对读者是不可见的。<br/>

当使用命名锚（named anchors）时，我们可以创建直接跳至该命名锚（比如页面中某个小节）的链接，这样使用者就无需不停地滚动页面来寻找他们需要的信息了。<br/>
<b>命名锚的语法：</b>
<a name="label">锚（显示在页面上的文本）</a>
<br/>
<b style="color:red">提示：</b>锚的名称可以使任何你喜欢的名字
<br/>
<b style="color:red">提示：</b>您可以使用 id 属性来替代 name 属性，命名锚同样有效。<br/>
</p>

<br/>
<b>实例</b>
<br/>
首先，我们在 HTML 文档中对锚进行命名（创建一个书签）：
<br/>
<a name="tips">基本的注意事项 - 有用的提示</a>
<br/>
然后，我们在同一个文档中创建指向该锚的链接：
<br/>
<a href="#tips">有用的提示</a>
您也可以在其他页面中创建指向该锚的链接：
<br/>
<a href="http://www.w3school.com.cn/html/html_links.asp#tips">有用的提示</a>
<br/>
在上面的代码中，我们将 # 符号和锚名称添加到 URL 的末端，就可以直接链接到 tips 这个命名锚了。
<br/>

<hr>
<h3>基本的注意事项-有用的提示</h3>
<b>注释：</b>请始终将正斜杠添加到子文件夹。假如这样书写<br/>href="http://www.w3school.com.cn/html"，就会向服务器产生两次 HTTP 请求。<br/>
这是因为服务器会添加正斜杠到这个地址，然后创建一个新的请求，就像这样：href="http://www.w3school.com.cn/html/"。
<br/>
<b style="color:red">提示：</b>命名锚经常用于在大型文档开始位置上创建目录。可以为每个章节赋予一个命名锚，然后把链接到这些锚的链接放到文档的上部。如果您经常访问百度百科，您会发现其中几乎每个词条都采用这样的导航方式。
<br/>
<b style="color:red">提示：</b>假如浏览器找不到已定义的命名锚，那么就会定位到文档的顶端。不会有错误发生。
<br/>
</hr>

<hr>
<h3>更多实例</h3>

<h4>在新的浏览器窗口打开链接</h4>
本例演示如何在新窗口打开一个页面，这样的话访问者就无需离开你的站点了。
<br/>
<a href="http://www.w3school.com.cn/" target="_blank">Visit W3School!</a>
<p>如果把链接的 target 属性设置为 "_blank"，该链接会在新窗口中打开。</p>

<h4>链接到同一个页面的不同位置</h4>
本例演示如何使用链接跳转至文档的另一个部分
<br/>
<p>
<a href="#C4">查看 Chapter 4。</a>
<br/>
<a href="#C17">查看 Chapter 17。</a>
</p>

<h5>Chapter 1</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 2</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 3</h5>
<p>This chapter explains ba bla bla</p>

<h5><a name="C4">Chapter 4</a></h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 5</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 6</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 7</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 8</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 9</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 10</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 11</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 12</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 13</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 14</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 15</h5>
<p>This chapter explains ba bla bla</p>

<h5>Chapter 16</h5>
<p>This chapter explains ba bla bla</p>

<h5><a name="C17">Chapter 17</a></h5>
<p>This chapter explains ba bla bla</p>

<h4>跳出框架</h4>
本例演示如何跳出框架，假如你的页面被固定在框架之内

<p>被锁在框架中了吗？</p> 

<a href="/readme.html" target="_top">请点击这里！</a> 
<hr>
<h4>创建电子邮件链接</h4>
本例演示如何链接到一个邮件。（本例在安装邮件客户端程序后才能工作。）

<p>
这是邮件链接：
<a href="mailto:someone@microsoft.com?subject=Hello%20again">发送邮件</a>
</p>
<p>
<b>注意：</b>应该使用 %20 来替换单词之间的空格，这样浏览器就可以正确地显示文本了。
</p>
<p>
这是另一个 mailto 链接：
<a href="mailto:someone@microsoft.com?cc=someoneelse@microsoft.com&bcc=andsomeoneelse2@microsoft.com&subject=Summer%20Party&body=You%20are%20invited%20to%20a%20big%20summer%20party!">发送邮件！</a>
</p>
<p>
<b>注意：</b>应该使用 %20 来替换单词之间的空格，这样浏览器就可以正确地显示文本了。
</p>
</hr>

</body>
</html>

