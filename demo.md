---
marp: true
theme: tongji
math: latex
---
<!-- _class: title -->
# 同济大学Marp主题
## 标题H2
这是正文

---
<!-- _class: chapter -->
# 这是章节页

---
# 标题H1
## 标题H2
### 标题H3
#### 标题H4
##### 标题H5
###### 标题H6
这是正文

---
# 基本
## 基本样式
这是正文
*斜体*
**强调**
> 引用块
---
# 列表
- 无序列表
- 无序列表
    - 无序列表
1. 有序列表
2. 有序列表
---
# 代码
```c++
#include <iostream>
using namespace std;
int main() {
    cout << "Hello World!" << endl;
}
```
## 行内代码
这是行内代码`code`

---
# 表格

| 表头 | 表头 |
|-----|-----|
|单元格|单元格|
|单元格|单元格|
|单元格|单元格|

---
# 公式
这是行内公式$a+b$
这是行间公式
$$
f(x) = \frac{1}{\sqrt{2\pi}\sigma}\mathrm{e}^{-\frac{(x-\mu)^2}{2\sigma^2}}
$$
---
# 文字与图片分栏显示
<div class="grid-two">
  <div>
  
## 左侧标题

左侧说明文字。此时图片只能使用HTML在`<div>`中用`<img>`插入

  </div>
  <div>
    <img src="images/dusk.jpg" style="width: 100%;">
  </div>
</div>
