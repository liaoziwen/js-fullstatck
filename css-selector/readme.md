！important         1，0，0，0，0    优先级最高
- 行内样式          1，0，0，0
- id                0，1，0，0
- class/伪类/属性选择器     0，0，1，0     :nth-child  伪类选择器       [type="text"]  属性选择器
- 标签选择器/伪元素  0，0，0，1            div   body  标签选择器       ::before  ::after  伪元素
- 通配符选择器       0，0，0，0            *  通配符选择器         >:父子    +:兄弟


.parent .child  选中的是.parent下面的.child  
.parent, .child  既能选中 .parent的元素，又能选中 .child的元素
.parent.child    选中的是既有 .parent的元素，又有 .child的元素