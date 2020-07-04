# 学习记录
**2020.06.30**
这是我的第一个仓库，体验一下github的使用。
***
**2020.07.01**
1. 初步了解一下Markdown语法
2. fork了一个项目，并基于此搭建了一个简易个人blog
***
**2020.07.02**  
1、了解什么是项目以及什么是项目经验  
2、参加面试
***
**2020.07.03**
1、学习KNN算法和朴素贝叶斯算法，简单了解了其优缺点和应用场景
***
**2020.07.04**
1、决策树算法
  1. 原理：基于经验做判断，并将做判断过程中的逻辑外显为树状图，包括构造和剪枝两个阶段；
  2. 使用场景：菁蓉行业用决策树做贷款风险评估；医疗行业用决策树做辅助诊断；电商行业用决策树进行销售额预测；
2、朴素贝叶斯算法
  1. 原理：基于特征属性的条件下求类别概率；
  2. 应用场景：中英文文本分类、情感分析、垃圾邮件识别等；
3、SVM算法：
  1. 原理：使样本集中的点到分类超平面的最小距离(分类间隔)最大化的过程；
  2. 应用场景：模式识别、分类尤其是二分类文本问题、回归分析；
4、KNN算法：
  1. 算法原理：近朱者赤，近墨者黑。算法三步骤：1）计算待分类物体与其他物体之间的距离；2）统计距离最近的K个邻居；3）K个邻居中那个分类最多，待分类物体就属于那一类；
  2. 应用场景：根据不同的距离计算公式，应用场景不同，如识别手写数字、划分电影类型等用欧式距离；而衡量用户对内容兴趣的区分度、推荐搜索等用遇险距离即夹角；
5、K-means算法：
  1. 算法原理：人以群分，物以类聚；1）随机确定K个点作为初始的类中心点；2）计算距离，将每个点分配到最近的类中心点，形成K类，然后重新计算每个类的中心点，常用均值法；3）重复第二步，直到类不发生变化，或者达到设置的最大迭代次数；
  2. 应用场景：
6、EM聚类算法：
  1. 算法原理：先通过假定的参数计算隐含变量(E步，Expectation)，然后将得到的隐含变量结果来重新估计参数，直到参数不再发生变化为止(M步，Maximization)
  2. 应用场景：探索分类、EDA时做降维探索等
7、关联规则挖掘：
  1. 算法原理：从数据集中发现项与项的关系，常用于购物篮分析，其中最常用的是Apriori算法，其原理为：1）求频繁项集(frequent itemset)的过程，频繁项集是支持度≥最小支持度阈值的项集；
  2. 使用场景：购物篮模型、捆绑消费、凑单推荐等
