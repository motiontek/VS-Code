
###自动索引
 [TOC]
 
###特征标签 
 @(示例)[马克飞象|帮助|Markdown]

###粗体
 **马克飞象**
  
###突出
`Ctrl + /` 
 
###列表
- 第一项
- 第二项
 
###引用
> 三人行必有吾师。    —— [孔子](http://baike.baidu.com/)

[链接名](http://www.example.com)或一个脚注[^demo]。
 
###代码
```Javascript
var emp = {	name:"Frank", age:45 };
```

```Python
代码内容
``` 
```Java
代码内容
```

### 表格
| Item      |    价格 | 数量  
| :--       | --:      | :--: 
| Computer  | 5600  |  5   
| Phone     |   120 |  12  
| Pipe      |    10 | 234  

###流程图
```flow
st=>start: 开始
e=>end: 结束
op1=>operation: 准备数据
op2=>operation: 计算处理
cond1=>condition: 是否正确?

st->op1->op2->cond1
cond1(yes)->e
cond1(no)->op1
```

###以及时序图:

```sequence
客户端->服务端: 给我姓名叫张三的员工信息
Note right of 服务端: 服务端响应
服务端-->客户端: 给你张三的信息
```

### LaTeX 公式

可以创建行内公式，例如 $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$。或者块级公式：

$$	x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$