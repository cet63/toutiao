# toutiao 街拍爬虫（半成品）


## 缘起
由于头条改用js渲染文章，原代码已无法使用。

简单看了下请求的文章结构，渲染内容就在页面的脚本中；于是整改思路就很清楚了：提取js脚本里的图片地址。

### 备注
* 由于是从js脚本里提取内容，如果爬虫改用js，想必更简单
* 修改代码的过程中，简便起见，去除了根据标题过滤内容的部分；因此会有一些不相干的图，要加上也很简单啦，把unicode码转回中文字符就ok了（。。逃）

