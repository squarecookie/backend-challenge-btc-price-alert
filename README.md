# 方饼干后端笔试 - 比特币价格监控

调用第三方API查询比特币（BTC）价格。当比特币价格在5分钟内的涨幅或者跌幅超过某个阈值时，记录该时间节点，价格，涨跌方向。

可用的API:
[非小号公共API](https://github.com/xiaohao2019/API-docs/blob/master/PublicApi_CN.md)


## 要求
* 可使用任意一种后端开发语言
* 价格变化的阈值通过配置导入

## 加分项
* 使用docker，将应用容器化
* 使用数据库记录数据
