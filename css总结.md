###css基础
####1. css书写位置
* 内嵌式：写在html head中的style标签中
* 外链式：单独的css文件 用link标签引入（rel href）
* 导入式：@import url() 有延迟 不常用
* 行内式：写在标签中的style属性中
* 注意：选择器间无符号

####2. css选择器
#####css2.1
* 标签选择器： 通常用于标签的初始化，如取消自带样式
*  id选择器：给元素指定唯一标识id，#id
*  class选择器：class 可以不唯一，选择一类元素  .class
*  复合选择器：
	- 后代选择器 以空格分隔
	- 交集选择器 以点号(.)分隔
	- 并集选择器（分组选择器） 以逗号分隔
*  伪类：指定要选择元素的特殊状态，a link visited hover active 爱恨准则 LOVE HATE

#####css3 
*  子选择器：div>p div的子标签p
*  相邻兄弟选择器：img+p img紧跟的p
*  通用兄弟选择器：p~pan p之后所有同级span
*  序号选择器：
   - first-child 第一个子元素
   - last-child 最后一个子元素
   - last-of-type 最后一个某类型子元素
   - nth-child(3) 第3个子元素   an+b   even 2n   odd 2n+1
   - nth-of-type(3) 第3个某类型的子元素
   - nth-last-child(3) 倒数第三个子元素
   - nth-last-of-type(3) 倒数第三个某类型的子元素
* 属性选择器：
   - img[alt]
   - img[alt=""]
   - img[alt^=""]
   - img[alt$=""]
   - img[alt*=""]
   - img[alt~=""] 用空格隔开
   - img[alt|=""] 以开头加-
* 伪类：
   - :empty 空标签
   - :focus 获取焦点的表单元素
   - :enabled 有效的表单元素
   - :disabled 无效的表单元素
   - :checked 已经勾选的单选或复选框
   - :root 根元素 即html标签
* 伪元素：  
   - ::before 必须设置content
   - ::after 必须设置content
   - ::selection 控制选中区域
   - ::first-letter 选中某块级元素的的第一个字母
   - ::first-line 选中某块级元素的的第一行全部文字
  

