
# 第一个MarkDown文档
[toc]
## 一、文字样例
### 序列及字体
  - 链接：[百度](https://www.baidu.com)
  - 链接：[Github](https://www.github.com)
  - 缩进样例  
  - 这是一段长文字，其中有几个文字需要**加黑**，效果如前所示。还有几个文字需要*斜体*，效果如前所示。 这里的这段文字有~~删除线效果~~，效果
### 文字块效果
接下来展示一段文字块，效果如下所示：
  > 引用整段文字块，效果参照这里.
  > 
  > 引用文字块第二部分
  > > 这里的文字是第二层引用，效果可见。
  > 
  > 引用文字块的结尾部分。
### 代码块效果
java代码
```java
if (TextUtils.isEmpty(text)) {
    return null;
}
```
python代码
```python
#!/usr/bin/env python3
    print("Hello, World!");
```
### 任务列表
- [ ] 选项一
- [ ] 选项二
- [x] 就选这里
### 文本高亮
这是一段==高亮==文本


---

### 2.公式举例
$f(x)=sin(x)+12$  
$f(x)=(abs(x+y)+cos(y))/(a+b)$  


### 3.图片样例
#### 两张图片并列
<figure class="half">
    <img src="../res/pic/pic2.jpeg" height="120"> <img src="../res/pic/pic1.jpeg" height="120">
</figure>

#### 三张图片并排显示
<figure class="third">
    <img src="../res/pic/pic1.jpeg"><img src="../res/pic/pic2.jpeg"><img src="../res/pic/pic1.jpeg">
</figure>

## 二、高级定制