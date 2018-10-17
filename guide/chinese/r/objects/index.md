---
title: Objects in R
localeTitle: R中的对象
---

R允许通过将数据存储在R对象中来保存数据。

## 什么是对象？

它只是一个名称，可用于调用存储的数据。例如，您可以将数据保存到a或b之类的对象中。

```r
> a <- 5 
 > a 
 [1] 5 
```

## 如何在R中创建一个对象？

1.  要创建R对象，请选择一个名称，然后使用小于号的符号`<` ， 后跟一个减号， `-` ，将数据保存到其中。这个组合看起来像一个 箭头， `<-` 。 R会制作一个物品，给它起你的名字，然后把它存放在里面 按照箭头。
    
2.  当你问R是什么时，它告诉你下一行。例如：
    

```r
> die <- 1:6 
 > die 
 [1] 1 2 3 4 5 6 
```

3.  您可以在R中为几乎任何您想要的对象命名，但是有一些规则。第一， 名称不能以数字开头。 其次，名称不能使用某些特殊符号，如`^, !, $, @, +, -, /, or *` ：
    
4.  R也理解大小写（或区分大小写），因此name和Name将引用不同的对象。
    
5.  您可以使用函数`ls()`查看已使用的对象名称。
    

## 参考

[官方文件](https://cran.r-project.org/manuals.html) [R博客中的R中的对象](https://www.r-bloggers.com/classes-and-objects-in-r/) [CRAN](https://cran.r-project.org/doc/manuals/r-release/R-lang.html)