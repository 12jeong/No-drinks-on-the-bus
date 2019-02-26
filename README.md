# No-drinks-on-the-bus

## EDA
library(GGally)
![EDA](/images/EDA_correlation1.png)
library(corrplot)
![EDA](/images/EDA_correlation2.png)
![EDA](/images/EDA_seoul_daypop.png)
![EDA](/images/EDA_seoul_nightpop.png)
![EDA](/images/EDA_seoul_people.png)
![EDA](/images/EDA_seoul_areasize.png)
![EDA](/images/EDA_seoul_caffecount.png)
![EDA](/images/EDA_seoul_sales.png)
![EDA](/images/EDA_seoul_buscount.png)
![EDA](/images/EDA_seoul_trashcount.png)

## Clustering
*gu k-menas
![K-means](/images/kmeans.png)
![K-means](/images/kmeans_graph.png)
*gu h-clust
![K-means](/images/cluster_average.png)
![K-means](/images/cluster_complete.png)
![K-means](/images/cluster_single.png)
*final gu cluster and characteristic
예산이 자치구 단위로 집행되어 정책이 시행 되기 때문에 구 단위 군집 분석이 적합함
초록색 군집의 경우 면적, 주간생활인구, 커피전문점수, 버스승차객 수가 많은 축임에 반해 쓰레기통 수가 적음을 알 수 있음
따라서 초록색 군집에 대해 분석시행
![K-means](/images/final_kmeans.png)
![K-means](/images/cluster_scatterplot.png)

## Correlation Network
*market correlation
![network](/images/market_cor.graph.png)

## PCA
*market pca

![PCA](/images/pca_result.png)

## Final
*
![Final](/images/관악구_서울대입구역.png)
![Final](/images/관악구_신림역.png)
![Final](/images/서초구_교대역.png)
![Final](/images/서초구_양재역.png)
