---
title: "Статистика по Covid-19 в Эстонии"
subtitle: "График обновляется"
slug: "covid-chart"
date: 2021-03-22T02:53:07+02:00
lastmod: 2021-03-22T02:53:07+02:00
draft: false
author: ""
authorLink: ""
description: "Image credit: [**Dan Counsell**](https://unsplash.com/photos/zIwAchjDirM"

tags: [charts]
categories: [Covid-19]

hiddenFromHomePage: false
hiddenFromSearch: false
toc:
  enable: false
math:
  enable: false
lightgallery: false
license: ""

#image: 
#  placement: 2
#  caption: 'Image credit: [**Dan Counsell**](https://unsplash.com/photos/zIwAchjDirM)'
#  preview_only: false
featured_image_caption: "Image: ImageSource" # quotation marks to allow colon
featured_image_alt: Alt tag for the featured image
featuredImage: ""
featuredImagePreview: "featured.jpg"
caption: "Image credit: [**Markus Winkler**](https://unsplash.com/photos/IrRbSND5EUc)"
# preview_only: true
---

Создали [**страницу**](/2021/covid-chart/) со статистикой по коронавирусу в Эстонии.

<!--more-->

{{< admonition info >}}
График <span style="color:#B03A5B">**обновляется**</span>
{{< /admonition >}}

**Статистика по Короновирусу**
 

{{< echarts >}}
{
"title": {
"text": "Ситуация по коронавирусу в Эстонии за 2021 год",
"top": "2%",
"left": "center"
},
"tooltip": {
"trigger": "axis"
},
"legend": {
"data": ["Положительный тест на коронавирус", "Процент выявленных", "Количество умерших"],
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
"data": ["11-03", "12-03", "13-03", "14-03", "15-03", "16-03", "17-03", "18-03", "19-03", "20-03", "21-03", "22-03", "23-03", "24-03", "25-03", "26-03", "27-03", "28-03", "29-03", "30-03", "31-03", "01-04", "02-04", "03-04", "04-04", "05-04", "06-04", "07-04", "08-04", "09-04", "10-04", "11-04", "12-04", "13-04", "14-04", "15-04", "16-04", "17-04", "18-04", "19-04", "20-04", "21-04", "22-04", "23-04", "24-04", "25-04", "26-04", "27-04"]
},
"yAxis": {
"type": "value"
},
"series": [
{
"name": "Положительный тест на коронавирус",
"type": "line",
"stack": "Total",
"data": [1956, 1357, 1586, 935, 1279, 1462, 1783, 1700, 1749, 1248, 1373, 993, 1062, 1553, 1429, 1151, 1151, 892, 584, 1202, 1009, 832, 901, 519, 462, 383, 899, 984, 757, 677, 639, 438, 269, 638, 549, 572, 478, 333, 543, 228, 536, 472, 436, 392, 390, 215, 163, 459]
},
{
"name": "Процент выявленных",
"type": "line",
"stack": "tal",
"data": [20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 17.1, 16.1, 17.8, 13.3, 12.3, 16.6, 16.1, 15.8, 12.3, 12.0, 12.4, 10.1, 11.4, 11.0, 10.8, 9.5, 6.4, 8.1, 8.2, 9.2, 11.1, 7.7, 7.8, 8.6, 6.1, 8.1, 9.1]
},
{
"name": "Количество умерших",
"type": "line",
"stack": "tal",
"data": [20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 20, 17, 16, 17, 15, 11, 12, 13, 14, 16, 14, 8, 9, 12, 8, 7, 6, 12, 10, 8, 4, 5, 11, 6, 11, 6, 6, 3]
}
]
}
{{< /echarts >}}  