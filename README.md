# Population flow - Wuhan City

<div align="center">
  <img src="https://github.com/leiii/population_flow/blob/master/population_flow_wuhan.png" width = "1000"><br><br>
</div>

利用 2015-16 年人口迁徙数据（基于手机位置）绘制的武汉市与其它城市的联系图。

## 从武汉市出发的目的地前20城市列表
* 4209：孝感市
* 4211：黄冈市
* 4403：深圳市
* 4210：荆州市
* 4206：襄阳市
* 3100：上海市
* 1100：北京市
* 4202：黄石市
* 4401：广州市
* 4212：咸宁市
* 4205：宜昌市
* 4290：仙桃市/潜江市/天门市
* 4207：鄂州市
* 4208：荆门市
* 4419：东莞市
* 4203：十堰市
* 4213：	随州市
* 4228：	恩施土家族苗族自治州
* 3301：杭州市
* 5000：重庆市

 
## 数据

[数据下载](https://github.com/leiii/population_flow/blob/master/wuhan_flow.csv)

数据来源：《基于手机位置数据的城市人口时空分布特征研究》，董磊，清华大学博士论文，2017年
 
## 字段名称
 
* pi：起始城市人口规模（数据来源：统计年鉴）
* pj：目标城市人口规模（数据来源：统计年鉴）
* loni：起始城市经度
* lati：起始城市纬度
* cityi.id：起始城市行政区划代码
* provi.id：起始城市所在省份行政区划代码
* lonj：目标城市经度	
* latj：目标城市纬度	
* cityj.id：目标城市行政区划代码
* provj.id：目标城市所在省份行政区划代码	
* flowij：流量强度
* distij：城市间距离
* sameprov：起始和目标城市是否位于同一省份（1：是，0：否）
 
 
