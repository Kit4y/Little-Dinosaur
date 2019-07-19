# 项目规划

课题：岗位薪资分析与薪资预测

## 第一次会议 2019/7/19

### 讨论问题

- 项目初步需求

- 项目分工

### 初步需求

1. 岗位薪资分析

    - 岗位查询，薪资排行(列表形式)

    - 某个岗位的全国分布情况(地图显示，选择岗位)

    - 对应岗位在某个地区的薪资水平，以及当地的物价生活水平等(图表显示，选择岗位和地区)

    - 根据岗位、薪资推荐地区和公司

2. 薪资预测：

    - 求职者设定地区、岗位、公司等信息后，预测今年招聘的最终薪资

    - HR 预测该公司今年应该发布的招聘薪资

### 分工

|模块|详细内容|负责人|
|---|---|---|
|爬虫|爬取51job招聘网数据，以及各城市物价、房价、消费等信息|zhang + wu|
|建模和调参、机器学习|主要根据招聘网数据进行建模、预测薪资|du + cao|
|web开发|前后端开发|li + liu|
