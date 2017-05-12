# 选择器
## 1.属性选择器
* [id ^= 'val'] 选择id里开头有val的元素
* [id $= 'val'] 选择id里结尾有val的元素
* [id *= 'val'] 选择id里包含有val的元素
## 2.伪元素选择器
*  li:first-line{...}设置对象内的第一行样式
*  li:first-letter{...}设置对象内的第一个字符的样式
*  li:before{content:"*";....}在li对象的内容前面添加content里面的字符，这里是添加*
*  li:after{content:"*";....}在li对象的内容后面添加content里面的字符，这里是添加*
## 3.结构性伪类选择器
* li:root：   匹配li元素在文档的根元素  
* li:not(s):  匹配不含有S选择符的元素li
* li:empty :  匹配没有任何子元素的元素li
* li:target:  匹配冒点连接中当前活动的目标元素
## 4.结构性伪类选择器
* li-first-child:匹配父元素的第一个子元素li
*   li-last-child: 匹配父元素的最后一个子元素li
