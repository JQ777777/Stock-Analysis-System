基于Spark的股票分析系统
利用大数据和spark技术，构建风险预警模型，提前识别潜在的市场风险，降低投资损失，此外通过深入分析历史数据和市场趋势，为投资者提供个性化的投资策略建议，提高投资回报率。

系统设有注册页和登录页，用户需要先登录才可以使用查询功能。登录后首页和查询页会显示当前登录的用户名和头像，头像旁边会出现退出登录按钮；页面包含导航栏，可以快捷导航到各页面；首页写明了系统功能简介，下方四个组块介绍四种查询功能，并可以点击跳转对应的查询页；

系统共提供三个查询功能：

1、单只股票k线查询：输入开始时间、结束时间、股票名称、查询数量，点击查询。结果呈现两张图，图1为股票k线图以及均线和涨幅线，图2为成交量和成交量均线；

2、两只股票对比查询：输入开始时间、结束时间和两只股票名称，点击查询。结果呈现两张图，分别为两只股票的k线和均线；

3、单日所有股票查询：输入待查询日期，点击查询，结果呈现为列表，显示当天所有股票的股票名称、开盘价、收盘价、最高价、最低价、涨幅和成交量。
