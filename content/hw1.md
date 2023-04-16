# 作业 1

1. 为什么我们在使用 Validation dataset 进行模型筛选后, 还要用另外的 Test dataset 来评估模型的预测精度? 为什么直接用 Validation dataset 来评估模型精度, 得到的结果会是有偏的?

    - 注: 实际应用中, 模型在 Validation dataset 上和 Test dataset 上的表现常常相差甚远. 以预测股票涨跌为例, 我们选择的模型可能在 Validation dataset 上的准确率超过 70%, 但在Test dataset 上的准确率只有不到 60%.


1. 阅读关于 Bias-Variance tradeoff 的进一步资料: [PDF](/hw/wiki.pdf). 简单谈几个教师在课上没有说到的要点, 此题中英文回答皆可.


1. 阅读倒数第二张幻灯片中的三张图, 并解释图中体现的
bias-variance tradeoff.

    - Hint:
  The three plots use the same data generation processes as the previous three examples. During the lecture, I have explained the MSE-flexibility curves from the perspective of overfitting. Here I want to see your explanations from the perspective of
  bias-variance tradeoff.
   
   



