### html基本标签
  如下图所示:
  ![[html/第1章/jpg/4.png]]

#### 标题标签
  ...
    代码:
      `<h1>这是标题</h1>`
    运行结果:
      ![[html/第1章/jpg/5.png]]
      h1~h6由最大到最小排序，之后的h7等都无效
      标题都是单独占一行自动换行，且都是自动加大加粗。

#### 注释
  ...
    代码:
      `<!--  这是注释的方法` 
      `可以多行也可以单行-->`
    这个注释内容不会被网页所解释，主要用来解释说明

#### 换行与段落
  ...
    代码:
    `<br>`
    可以用来对页面两行内容进行换行，如果不用网页中就是挨着的不会换行只会展示一个空格。
    段落代码:
      `<p>这是第一段的内容<br>这是第二段的内容</p>`
    运行结果:
      ![[html/第1章/jpg/6.png]]
      所展示的内容由 `<br>` 所断开换行
      两个段落之间也会自动换行比如
      `<p> 第一段 </p>`
      `<p> 第二段 </p>`
      在里网页中展示的第一段与第二段是换行展示的。

#### 水平线标签
  ...
    代码:
    `<hr>`
    运行结果:
       ![[html/第1章/jpg/7.png]]
       ==标题与段落之间的水平线就是它的最终展示结果。==

#### 字体倾斜
  ...
    代码:
      `<em>这是字体倾斜标签</em>`
    运行结果:
      ![[html/第1章/jpg/8.png]]
      使字体有倾斜感
      这个标签不能独占一行

#### 字体加粗
  ...
    代码:
      `<strong>加粗</strong>`
    也无法独占一行