# 金融投资学

湖南大学 2023 年春季课程.
所有课程资料均会发布于此.
本课程讨论统计学习(or 机器学习)在金融经验研究中的应用.


## 参考书

[1] *An Introduction to Statistical Learning,*
by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani.
[豆瓣页面](https://book.douban.com/subject/21706191/).

- 英文第二版 [PDF](https://hastie.su.domains/ISLR2/ISLRv2_website.pdf), 书籍官网[链接](https://www.statlearning.com) (境外网站, 可能需要科学上网)
- 第一版中文翻译 [PDF](https://hlei.lanzouf.com/iu7Qn0t6uqob), 课程视频 [bilibili 链接](https://www.bilibili.com/video/BV1NW41177q4/)
- 统计计算: 每个章节的末尾, 均有对应的 R 语言实操环节 (R Lab). 如果你写 python,
可以参考[这个 github 项目](https://github.com/hardikkamboj/An-Introduction-to-Statistical-Learning).
我们课上只讲 R, 但你可以用任何你喜欢和擅长的工具来完成课程作业.


[2] *Machine Learning in Business: An Introduction to the World of Data Science*,
by John Hull.

- 英文第二版 [PDF](notes/ml_john_jull.pdf)

## 课堂资料

4月14: 统计学习简介 (ISLR Ch2)
- 课程说明 [PDF](slides/w1a-course-intro.pdf),
[source](slides/w1a-course-intro.marp);
- 监督学习与非监督学习
[PDF](slides/w1b-intro-stat.pdf),
[source](slides/w1b-intro-stat.pdf);
- 监督学习简介, bias-variance tradeoff
[PDF](slides/w1c-intro-stat-learning.pdf),
[source](slides/w1c-intro-stat-learning.marp).


4月21: 线性模型 (ISLR Ch3)
- 一元回归 [PDF](slides/w2a-linear-regression.pdf), [source](slides/w2a-linear-regression.marp);
[最小二乘动图](slides/fig/LS.gif);
- 多元回归 [PDF](slides/w2b-multi-linear.pdf),
[source](slides/w2b-multi-linear.marp) 


4月28: 模型选择, R 语言入门 (ISLR Ch6)

- 模型选择简介, 常见筛选准则 [PDF](slides/w3a-model-selection.pdf), [source](slides/w3a-model-selection.marp)
- R 语言简介
[notes](notes/w3-intro2R.html),
[source](notes/w3-intro2R.qmd)

5月5: 交叉验证, 自助法, 收缩估计 (ISLR Ch5, Ch6)

- R 语言简介: 线性回归
[notes](notes/lab-linear.html)
[source](notes/lab-linear.qmd)

- 交叉验证 (Cross-validation)
[PDF](slides/cv.pdf),
[source](slides/cv.marp)

- 统计学实验: 自助法
[notes](notes/lab-boot.html),
[source](notes/lab-boot.qmd)

- 统计学实验: James-Stein 统计量
[notes](notes/w3-JS.html),
[source](notes/w3-JS.qmd)

<!-- 收缩估计 (Shrinkage Estimation) -->

## 作业

- [作业一](hw/hw1)

- 作业二
