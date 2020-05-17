# 目录
###### 代码
```
* <a href="#title">标题</a>
* <a href="#fontstyle">字体</a>
* <a href="#quote">引用</a>
* <a href="#pic">图片</a>
* <a href="#href">超链接</a>
* <a href="#list">列表</a>
* <a href="#table">表格</a>
* <a href="#code">代码</a>
* <a href="#flow">流程图</a>
```
###### 呈现
* <a href="#title">标题</a>
* <a href="#fontstyle">字体</a>
* <a href="#quote">引用</a>
* <a href="#pic">图片</a>
* <a href="#href">超链接</a>
* <a href="#list">列表</a>
* <a href="#table">表格</a>
* <a href="#code">代码</a>
* <a href="#flow">流程图</a>

# <a name="title">标题</a>
###### 代码
```
# <a name="title">标题</a>
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```
###### 呈现
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题


# <a name="fontstyle">字体</a>
###### 代码
```
**这是加粗的文字**  
*这是倾斜的文字*  
***这是斜体加粗的文字***  
~~这是加删除线的文字~~
```
###### 呈现
**这是加粗的文字**  
*这是倾斜的文字*  
***这是斜体加粗的文字***  
~~这是加删除线的文字~~


# <a name="quote">引用</a>
###### 代码
```
>这是引用的内容
>>这是引用的引用的内容
```
###### 呈现
>这是引用的内容
>>这是引用的引用的内容


# <a name="pic">图片</a>
###### 代码
`![github图标](https://timgsa.baidu.com/timg?image&quali... "github")`
###### 呈现
![github图标](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1589698907882&di=884512eb567550778ad1d282753abfd8&imgtype=0&src=http%3A%2F%2Fku.90sjimg.com%2Felement_origin_min_pic%2F00%2F86%2F40%2F1756eb4af1504bf.jpg "github")


# <a name="href">超链接</a>
###### 代码
`[davy's github](https://github.com/davy0118/tools "davy's github")`
###### 呈现
[davy's github](https://github.com/davy0118/tools "davy's github")


# <a name="list">列表</a>
###### 代码
```
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
```
###### 呈现

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


# <a name="table">表格</a>
###### 代码
```
序号|姓名|年龄|住址
---|---|---
1|davy|100|北京
```
###### 呈现
序号|姓名|年龄|住址
---|---|---
1|davy|100|北京


# <a name="code">代码</a>
`import cn.davy.learn.*`
```
int sum(int... values) {
   int v = 0;

   for(int vi : values) {
      v += vi;
   }
   
   return v;
}
```


# <a name="flow">流程图</a>
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```