javascript的组成：1.ECMAScript（5.1）基本语法（现已更新至6，但有兼容问题）
                 2.BOM浏览器对象模型
                 3.DOM文档对象模型（页面）
常用场景：1行为交互 2数据交互 3逻辑交互

特效交互：用js改变样式或者html结构

console.log()在控制台输出信息。

函数名（）  正常调用（非事件调用）
el.onclick=函数  事件调用

变量：用来储存任意类型的数据

关键字：正在使用的字
保留字：将来可能会使用的字

document.querySelector("")  根据一个css选择器来获取元素  （“.box”） （“#box”）
注意事项：当选择器匹配多个元素时，只能找到第一个
         querySelector是h5中新增的方法，不支持IE8及以下
         
属性操作：读操作：获取
         写操作：修改，增加，删除
注意：el.style属性，操作是元素的行间样式，console.log（）获取不到
     innerHTML元素中从开始到结束之间的内容
     
数据类型（目前接触）：1数字
                   2字符串，放在一对引号之间的0到多个字符，目前接触的属性值都是字符串。
                   
                   
css：box-sizing 允许以某种方式定义某种元素，以适应制定区域。
     resize:none 规定是否可由用户调整元素尺寸。
     font：14px/28px "宋体"
     ul li:nth-of-type(2n){background:#f1f1f1}  隔行变色
     
     获取表单元素时，请使用value  例如：textarea
