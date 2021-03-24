---
layout:  post 
title: "Covid-19"
date: 2021-03-21T11:04:49+02:00
draft: false
image: 
  placement: 2
  caption: 'Image credit: [**Markus Winkler**](https://unsplash.com/photos/IrRbSND5EUc)'
  preview_only: true
math:
  enable: true
featuredImagePreview: "featured.jpg"  
---

**Статистика по Короновирусу**  

{{< echarts >}}
{
"title": {
"text": "Ситуация по короновирусу в Эстонии за 2021 год",
"top": "2%",
"left": "center"
},
"tooltip": {
"trigger": "axis"
},
"legend": {
"data": ["Положительный тест"],
"top": "10%"
},
"grid": {
"left": "5%",
"right": "5%",
"bottom": "5%",
"top": "20%",
"containLabel": true
},
"toolbox": {
"feature": {
"saveAsImage": {
"title": "Save as Image"
}
}
},
"xAxis": {
"type": "category",
"boundaryGap": false,
"data": ["11-03", "12-03", "13-03", "14-03", "15-03", "16-03", "17-03", "18-03", "19-03", "20-03", "21-03", "22-03", "23-03", "24-03"]
},
"yAxis": {
"type": "value"
},
"series": [
{
"name": "Положительный тест на короновирус",
"type": "line",
"stack": "Total",
"data": [1956, 1357, 1586, 935, 1279, 1462, 1783, 1700, 1749, 1248, 1373, 993, 1062. 1553]
}
]
}
{{< /echarts >}}  
