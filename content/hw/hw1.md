# 作业 1

作业一均为问答题, 你可以任选一种提交方式:

1. **纸质版.** 手写答案, 在课上将纸质版答案交给任课老师.
请尽量做到字迹工整. 如果你自认为字迹很难辨认, 请选择提交电子版.

2. **电子版.** 你可以使用 Word 或 LaTeX 来完成作业, 提交前请先确保文件为 PDF 格式.
**教师只接受 PDF 格式的文件.** 

    - 作业一[在线提交地址](https://workspace.jianguoyun.com/inbox/collect/c45b72070ad54b349b5ab5bd9877e76c/submit)


## 问题

1. 为什么我们在使用 Validation dataset 进行模型筛选后, 还要用另外的 Test dataset 来评估模型的预测精度? 为什么直接用 Validation dataset 来评估模型精度, 得到的结果会是有偏的?

    - 注: 实际应用中, 模型在 Validation dataset 上和 Test dataset 上的表现常常相差甚远. 以预测股票涨跌为例, 我们选择的模型可能在 Validation dataset 上的准确率超过 70%, 但在Test dataset 上的准确率只有不到 60%.


1. 阅读关于 Bias-Variance tradeoff 的进一步资料: [PDF](/hw/wiki.pdf). 简单谈几个教师在课上没有说到的知识点, 此题中英文回答皆可.


1. 阅读课上[幻灯片中,](/slides/w1c-intro-stat-learning.pdf)
倒数第二张幻灯片中的三张图, 并解释图中体现的
bias-variance tradeoff.
    - *Hint:*
  The three plots use the same data generation processes as the previous three examples. During the lecture, I have explained the MSE-flexibility curves from the perspective of overfitting. Here I want to see your explanations from the perspective of
  bias-variance tradeoff.
   
   



