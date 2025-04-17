---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
carousels:
  - images: 
    - image: /sliders/slider1.jpg
      title: "2024"


---

<style>
.main-content {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}

.sliderBar {
  flex: 4;

  border-radius: 8px;

}

.sliderText {
  flex: 5;
  background-color: #fff;
  border-radius: 8px;
  padding-top:1rem;
}

.carousel__holder {
  width: 100%;
  height: 90%;
}

@media (max-width:768px){
  .main-content{
    flex-direction:column;
  }
  .sliderBar{
    max-width:100%;
    order:0;
  }
  .sliderText{
    order:1;
  }
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# 👨‍🏫 简介 {#Intro}
周梦杰，博士，副教授，硕士研究生导师，“世承人才计划”青年优秀人才，湖南省测绘地理信息学会地图专委会委员。主要研究方向为时空数据挖掘和地理信息可视化。近年来在以一作或通讯在 IJGIS、CEUS、CAGIS、GA、测绘学报等国内外知名期刊发表论文20余篇。主持国家自然科学基金、湖南省自然科学基金项目等多项课题，曾获国家测绘地理信息局测绘科技进步二等奖、湖南师范大学青年教师课堂教学竞赛二等奖、十佳教学设计等多项荣誉。


<!-- 
{% include carousel.html height="50" unit="%" duration="5" number="1" %}

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In class</div><img src='images/in class.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


</div>

</div>

-->

<div class="main-content">
  <div class="sliderBar">
    {% include carousel.html height="50" unit="%" duration="5" number="1" %}
  </div>
  <div class='sliderText' markdown="1">


**讲授课程**

- 地图学（本科生课程）
- MATLAB和R应用与开发（本科生课程）
- 地图设计与制作（本科生课程）
- 地图表达与地图分析（硕士研究生课程）
- 地图学与GIS研究新进展（博士研究生课程）


**研究方向**

- 时空数据挖掘与可视化

</div>
</div>




# 👨🏻‍🎓 研究生 {#postgraduate}
- 在读： 王钰辉 陈慧颖 李伊戈 刘莎莎 
- 已毕业： [阳孟杰]() [符青扬]() 


# 📝 主要成果 {#publication} 

- Yang, M., **Zhou, M.**\*, He, X.\*, et al. (2025). Incremental spatiotemporal flow colocation quotient: a new spatiotemporal association analysis method for geographical flows. *International Journal of Geographical Information Science*.
- 符青扬, **周梦杰***, 李伊戈, 陈伟涛(2025). 面向聚合型地理流的双变量时空关联分析方法. *测绘学报*, 54(3): 552-562.
- He, Z., Gu, Y., ... **Zhou, M.***.(2025).Analyzing the Joint Influence of Urban Facilities and Street Perception Characteristics on Street Robbery. *Journal of Geovisualization and Spatial Analysis*,9(1), article number 23.
-  **Zhou, M.***, Yang M., Ai, T., et al. (2024). Rethinking the null hypothesis in significant colocation pattern mining of spatial flows. *Journal of Geographical Systems*, 26:375-405.
- Fu, Q.,  **Zhou, M.***, Li, Y., et al. (2024). Flow Spatiotemporal Moran’I: Measuring Spatiaotemporal Autocorrelation of Flow Data. *Geographical Analysis*.
- **周梦杰**, 阳孟杰*, 陈慧颖, 等. (2024). 面向地理流的时空交叉K函数方法. *测绘学报*, 53(8): 1644-1655.
- 王钰辉, 阳孟杰,**周梦杰***,等. (2024). 面向地理流的双变量时空扫描统计方法.* 测绘科学*, 49(1):204-215．
-  **Zhou, M.**\*, Yang, M.\*, Chen, Z. (2023). Flow colocation quotient: Measuring bivariate spatial association for flow data.* Computers, Environment and Urban Systems*. 99, 101916.
-  **Zhou, M.**, Fu, Q., Li, Y., et al. (2023). Discovering spatiotemporal flow patterns: where the origin–destination map meets empirical orthogonal function decomposition, *Cartography and Geographic Information Science*, 50(2), 113-129.
- Wu, C.,  **Zhou, M.***, Liu, P., & Yang, M. (2021). Analyzing COVID-19 using multisource data: An integrated approach of visualization, spatial regression, and machine learning. *GeoHealth*, 5, e2021GH000439.
- Yang, M., Chen, Z.,  **Zhou, M.***, Liang, X., Bai, Z. (2021). The Impact of COVID-19 on Crime: A Spatial Temporal Analysis in Chicago. *ISPRS Int. J. Geo-Inf*. 10, 152.
- Yu, Q., Gu, Y., Yang, S.  **Zhou, M.***. (2021). Discovering Spatiotemporal Patterns and Urban Facilities Determinants of Cycling Activities in Beijing. *Journal of Geovisualization and Spatial Analysis*, 5, 16.
-  **Zhou, M.**, Ai, T.*, Wu, C., et al. (2019). A visualization approach for discovering colocation patterns. *International Journal of Geographical Information Science*, 33(3), 567-592. 
- Ai, T.,  **Zhou, M.**, Tian, J., & Ye, N. (2016). Origin-destination (OD) of the interprovincial floating population of China. *Journal of Maps*, 12: 577-583. 
-  **Zhou, M.**, Hu, W. & Ai, T. (2020). Multi-level thematic map visualization using the Treemap hierarchical representation model. *Journal of Geovisualization and Spatial Analysis*, 4, 12. 
-  **Zhou, M.**，Cheng, Y., Ye, N., & Tian, J. (2017). Effectiveness and Efficiency of Using Different Types of Rectangular Treemap as Diagrams in Cartography. In *Advances in Cartography and GIScience*. Springer. 
- 艾廷华, **周梦杰** & 李晓明. (2017). 网络空间同位模式的加色混合可视化挖掘方法. *测绘学报*, 46(6): 753-759. 
-  **Zhou, M.**, Tian, J., Xiong, F., & Wang, R. (2017). Point grid map: a new type of thematic map for statistical data associated with geographic points. *Cartography and Geographic Information Science*, 44(5): 374-389. 
-  **Zhou, M.**, Wang, R., Mai, S., & Tian, J. (2016). Spatial and temporal patterns of air quality in the three economic zones of China. *Journal of Maps*, 12: 156-162.
- 艾廷华, **周梦杰** & 陈亚婕. (2014). 专题地图属性信息的 LOD 表达与 TreeMap 可视化. *测绘学报*, 42(3): 453-460. 	

# 🔥 承担课题与项目 {#project}
- 国家自然科学基金青年科学基金项目，“色彩混合原理支持下的空间同位模式可视化挖掘”，2020-2022，主持
- 湖南省自然科学基金青年科学基金项目，“地理流的时空加权同位系数方法研究”，2023-2025，主持
- 湖南省教育厅优秀青年项目，“面向聚合型地理流的时空Moran's I方法研究”，2024-2026，主持
- 湖南省教育厅科学研究项目，一般项目，“街道网络空间局部同位模式可视化挖掘方法研究”，2019-2021，主持
- 数字制图与国土信息应用工程自然资源部重点实验室开放研究基金项目， 2019-2020，“街道网络视角下犯罪与城市设施空间关联的可视化挖掘”，主持
- 国家自然科学基金重点项目，“网络众源地理信息在线式尺度变换原理与方法”，2016---2020，参与
- 国家科技基础性工作专项，“新世纪版《中华人民共和国国家大地图集》编研”，2013-2018，参与


# 🎖 指导获奖 {#awards} 
- 程雪萍等，《中国2010年人口系列地图》“SuperMap杯第十六届全国高校GIS大赛”制图组,一等奖.
- 于沁玥等 “共享单车骑行模式的时空特征分析”大学生创新训练项目（省级）, 已结题.
- 陈哲，优秀本科毕业论文.


# 📖 教育经历 {#education} 
- 2014.9-2017.6 武汉大学 资源与环境科学学院 地图制图学与地理信息工程 博士 (导师：艾廷华教授)
- 2012.9-2014.6 武汉大学 资源与环境科学学院 测绘工程 硕士 (导师：艾廷华教授)
- 2008.9-2012.6 武汉大学 资源与环境科学学院 地理信息系统 学士




{% include text-expand.html %}
