---
title: "R Code分享"  # 文章标题，在网也中显示的标题
date: 2019-04-13  # 创建日期
lastmod: 2019-04-14  # 最后修改日期
draft: false  # =true为草稿，不会生成相应的网页
#slug: ""  # 所生成网页的地址后缀，若未设置，会根据文件名生成地址
keywords: [R, 学习资料]  # 关键字
tags: [R, 学习资料]  # 标签，会将此文章添加到指定的标签下
categories: [R, 学习资料]  # 分类，会将此文章添加到指定的分类下
author: "Yu Group"  # 作者
---

**R code示例书写规范：**

1. 第一行注释说明R code的用途及作者
2. 第二行开始进行代码的书写，尽量选择R自带数据进行演示，若数据格式不同，需提供数据
3. 对每一步进行注释，注释若是独立的一行则在行首输入`#`后空1格，然后开始注释，若注释紧接代码后面，先空2格，`#`，然后空1格进行注释。推荐阅读：[R代码书写规范](<https://google.github.io/styleguide/Rguide.xml>)）

第一行注释示例如下，在输入完用途后输入4个`-`再添加作者信息（这样复制到Rstudio中可以生成标题）

```markdown
​```R
# 代码用途 ---- by Author
​```
```

效果如下：

```R
# 代码用途 ---- by Author
```

目前分为**数据处理**、**统计模型**、**数据可视化**三个板块（一级标题），可根据需要增加

每个示例可添加相应的二级标题，便于通过目录查看

# 数据处理

## 删除重复值

```R
# 删除重复值 ---- by Si Shuting
baseold<-baseold[!duplicated(baseold[,c(7)]),]  # 按某列相同删除
```

# 统计模型

# 数据可视化


