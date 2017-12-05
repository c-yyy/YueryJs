# YueryJs
cover by jQuery
# YueryJs 使用方法
a javascript framework for operating dom and string<br/>
会用jquey就会用YueryJs<br/>
YueryJs选择器有两种写法： Y( 选择器 ) 和 $( 选择器 )<br/>
YueryJs的加载： Y( function(){} )    $( function() {} );<br/>

# 选择器用法
YueryJs完全支持CSS3选择器,下面列举部分用法<br/>
* 基本选择器( id, class, 元素 )
```
$("#box").css( "border", "1px solid #09f" );
$(".box").css( "border", "1px solid #09f" );
Y("div").css( "border", "1px solid #09f" );
```
* 后代，子代选择器
```
Y("body p").css( "border", "2px solid #09f" );
Y("body > p").css( "border", "2px solid #09f" );
```
* 属性选择器
```
Y( "[id]" ).css( "border", "1px solid #09f" );
Y( "[id][class]" ).css( "border", "1px solid #09f" );
Y( "[data-target]" ).css( "border", "1px solid #09f" );
Y( "[class*=desc]" ).css( "border", "1px solid #09f" );
Y( "[class^=desc]" ).css( "border", "1px solid #09f" );
Y( "[class$=desc]" ).css( "border", "1px solid #09f" );
```
* 过滤选择器
```
Y( "div:nth-child(1)").css( "border", "1px solid #09f" );
Y( "div:nth-of-type(1)").css( "border", "1px solid #09f" );
Y( "div p:nth-of-type(1)" ).css( "border", "1px solid #09f" );
```
V1.0.0目前支持的功能有
====================
事件绑定，选择器，DOM操作，动画，工具方法，插件扩展
# 事件相关方法
* delegate
* on
* hover
# 选择器函数
* lt
* gt
* eq
# dom与其他操作
* size
* before
* after
* append
* prepend
* addClass
* removeClass
* hasClass
* toggleClass
* css
* attr
* each
* val
* html
* empty
* find
* parent
* children
* parents
* siblings
* next
* prev
* get
* getDom
* index
# 动画方法
* animate
* show
* hide
* toggle
# 工具方法
* isNum
* trimLeft
* trimRight
* trim
* parseHtmlTag
* isArray
* toArray
* flatten
# 插件扩展
* extend
