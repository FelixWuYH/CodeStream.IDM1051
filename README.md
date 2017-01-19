# CodeStream.IDM1051
Course: Introduction to Data Mining

Rcurl套件，tm 套件，wordcloud套件
用R進行中文 text Mining
http://www.voidcn.com/blog/faith_mo_blog/article/p-3195628.html

xmlview package
在 RStudio 檢視 xml/html 的工具：xmlview Package
http://leoluyi.logdown.com/posts/432582-xmlview-package

httr套件
R 使用 httr 套件抓取網路資料教學：以 SNP Annotation 為例
https://blog.gtwang.org/r/r-httr-package-snp-annotation-examples/

xml2
手把手教你 R 語言資料分析實務/張毓倫&陳柏亨
http://www.slideshare.net/tw_dsconf/r-64232974

rjson
Using R to download and parse JSON: an example using data from an open data portal
http://zevross.com/blog/2015/02/12/using-r-to-download-and-parse-json-an-example-using-data-from-an-open-data-portal/

Quantmod
如何使用R 的 Quantmod 套件快速蒐集股價資訊並計算技術指標?
https://www.youtube.com/watch?v=BMhk2W2CTI8

data.table
使用data.table package读取大体量数据
http://www.seekingqed.com/programming/r/datatable

https://cran.r-project.org/web/packages/wordcloud/wordcloud.pdf

devtool套件，rga套件
用R軟體抓取GA資料－網站大數據的第一步
http://www.analyticsdavis.com/2016/02/analysis-ga-data-by-R.html

# rvest套件 範例
library(rvest)
url = "https://www.dcard.tw/f"
dcard = read_html( url, encoding = "UTF-8" )
title = dcard %>% html_nodes('strong') %>% html_text()
title = title[ title[] != title[1:4] ]
title
