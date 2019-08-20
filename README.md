# hkipo_firstday_performance
## 目的：研究港股ipo首日收益由哪些因素影响。
## 1 数据收集&数据清洗&特征工程
### 1.1 收集非财务数据
        1）收集2014.9.29-2017.7.19 期间在港ipo公司名单：来自GitHub crownpku/hk_ipo_prediction；
        2）收集2017.7.21-2019.7.5 期间在港ipo公司名单：从aastock新股频道上爬取；
        3）根据上述股票名单，收集ipo相关信息，如首日涨跌幅、保健人、所在板块等信息。
        file：ipo_list_collection.ipynb >>> ipo_info.txt
### 1.2 收集财务数据
        1）从aastock上爬取每只股票的资产负债表、利润表简表，分别建立txt文件储存；
        2）将每只股票的所需指标,如营业收入、总资产，按属于资产负债表或利润表，分别汇总成bs.txt、is.txt。
        file：financial_collection.ipynb >>> bs.txt is.txt
### 1.3 汇总财务数据和非财务数据；数据清洗；特征工程
        file：data_cleaning_feature_building.ipynb >>> ipo_20190808.xlsx 
        
## 2 数据分析  
阶段分析1 file：港股打新是“从地上捡钱吗”？.pdf
(***进行中***）

        
