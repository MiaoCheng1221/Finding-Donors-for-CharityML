# Finding-Donors-for-CharityML
Udacity project 2
CharityML 是一家位于硅谷核心地带的慈善机构，它致力于为想学机器学习的学生提供经济上的帮助。在社区中发出了32000多封捐赠信之后，他们发现他们收到的每一笔捐赠，都来自年收入5万美金以上的人。为了拓展他们的捐赠池，CharityML决定向加州居民发送一封信，信只发给那些最有可能捐助的人。因为加州的工作人群有一千五百万， CharityML雇佣你来帮他们构建一个最好的算法，来识别最有可能的捐赠者以降低发送信件的成本。
目标: 评估和优化几个不同的监督学习算法来决定哪个算法能给出最高的捐赠者识别率，以降低总计的发信数量。

准备数据和评估模型，这里简单预测准确率和f1 score，模型选择了random forest和logistic regression，和decision tree
优化结果时候选择了random forest，并且用feature importance找出重要特征
