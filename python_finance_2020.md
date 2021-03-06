

<div align='center' ><font size='5'>浙江工商大学2020/2021学年第一学期考试试卷(A)</font></div>



课程名称： **Python在金融中的应用**    考试方式：**独立作业**

班级名称：                                              学号：                                       姓名：

| 题号 | 一   | 二   | 三   | 四   | 合计 |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 满分 | 25   | 25   | 25   | 25   | 100  |
| 得分 |      |      |      |      |      |



**注意事项：**

1. 请大家务必独立完成，独立大作业视作考试，请不要抄袭。

2. 判分会综合考虑代码和运行结果，因此如果运行结果发生问题，可以仅提供代码。

3. 请尽可能给代码加上注释。代码可以用图片黏贴的形式，作图的结果请不要用截图，可以使用插入图片的方式。 

4. 在完成作业要求的基础上，鼓励大家根据自己的理解做适当的拓展，并请在代码上做出明确的注释。

5. 请大家注意版面的整洁和清晰程度，鼓励大家使用Markdown模板，也可以使用Word模板。电子版务必转成pdf格式。 

   

   **作业最晚提交时间： 2021年1月16日中午12点   烦请每个班派一位代表联系我，将纸质版和电子版的作业交至我处。**



##### 作业 一 

请从Tushare中导入至2018年1月1日至2021年1月1日5支股票（任选）的收盘价，并生成一个数据框 DataFrame。 计算每天每支股票的涨跌幅，并计算累计涨跌幅序列。针对5支股票的涨跌幅，计算这5支股票收益率的协方差和相关系数。


 假设投资者A，他采用投资并持有的策略，在2018年1月1日后的第一个交易日，购买了5支股票，每支100万元。计算每个交易日A先生持有的每支股票市值情况并可视化，同时再计算每个交易日A先生投资组合的整体市值并可视化。


 假设投资者B，她采用定投的方式，自2018年1月1日后的第一个交易日起，每天以当日收盘价对每支股票购买100股，计算每个交易日B女士持有的每支股票的盈亏情况并可视化，同时再计算每个交易日B女士投资组合的整体盈亏情况，并可视化。



##### 作业 二 

使用Tushare的命令找出随机100个场外公募基金，并找出它们在过去一年的调整后净值。计算它们各自在过去一年中的收益（不到一年的需将其年化）。找到它们各自最近的基金经理的情况，看看收益和基金经理的学历和性别是否有关系（可以使用其他的特征）。



##### 作业 三

使用爬虫爬取最近3个月每日的新浪新闻（可以使用讲义中的方法）。将新闻按照日进行分组，并对工作日的新闻进行舆情分析，使用Snow_NLP对于新闻进行打分，并计算每日的平均舆情得分。将舆情得分与当期的股票指数进行比较，计算它们两者间的相关系数，进而判断使用舆情分析是否可以做到预测股市的变化。



##### 作业 四

使用Tushare任取场内或者场外基金历史超过2年的200个公募基金，取得过去两年的基金净值序列，通过计算夏普比率（可任意设定无风险利率），来找到19年表现最好的50个基金。通过计算平均收益率，找到2020年表现最好的50个基金。看看有多少基金在其夏普比例和平均收益率的表现是一致的。