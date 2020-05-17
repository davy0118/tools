# 目录
* <a href="#fontstyle">字体</a>


# 标题
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题


# <a name="fontstyle">字体</a>
**这是加粗的文字**  
*这是倾斜的文字*  
***这是斜体加粗的文字***  
~~这是加删除线的文字~~


# 引用
>这是引用的内容
>>这是引用的引用的内容


# 图片
![github图标](https://github.com/davy0118/tools/blob/master/markdown/github.jpg ''github'')


# 超链接
[davy's github](https://github.com/davy0118/tools "davy's github")


# 列表
* 水果
   1. 橘子
   2. 苹果
* 蔬菜
   * 白菜
   * 胡萝卜
* 其它

1. 水果
2. 蔬菜
3. 其它


# 表格
序号|姓名|年龄|住址
---|---|---
1|davy|100|北京


# 代码
`import cn.davy.learn.*`
```
int sum(int... values) {
   int v = 0;

   for(int vi in values) {
      v += vi;
   }
   
   return v;
}
```


# 流程图
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```