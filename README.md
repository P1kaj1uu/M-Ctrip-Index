# 携程旅行移动端首页

原理：主要采用flex布局

|    父项属性     |                        说明                         |
| :-------------: | :-------------------------------------------------: |
| flex-direction  |                    设置主轴方向                     |
|    flex-wrap    |                 设置子元素是否换行                  |
|    flex-flow    | 复合属性，相当于同时设置了flex-direction和flex-wrap |
| justify-content |             设置主轴上的子元素排列方式              |
|  align-content  |          设置侧轴上的子元素排列方式(多行)           |
|   align-items   |          设置侧轴上的子元素排列方式(单行)           |

|  子项属性  |                         说明                          |
| :--------: | :---------------------------------------------------: |
|    flex    |             子项目占的份数，可以是百分数              |
| align-self |             控制子项自己在侧轴的排列方式              |
|   order    | 定义子项的排列前后顺序，默认是0，数值越小，排列越靠前 |

原版效果：

![image-20220426130449819](C:\Users\邓涛涛涛儿er\AppData\Roaming\Typora\typora-user-images\image-20220426130449819.png)

完成效果：

![image-20220426130641783](C:\Users\邓涛涛涛儿er\AppData\Roaming\Typora\typora-user-images\image-20220426130641783.png)