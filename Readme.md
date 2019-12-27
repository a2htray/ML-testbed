
* [数据来源说明](#数据来源说明)
    * [Cluster](#cluster1)
    * [Regression](#regression1)
    * [onehot](#onehot1)
* [参考](#参考)
    * [Cluster](#cluster2)
        * [kmeans](#kmeans1)
    * [onehot](#onehot2)


# 数据来源说明

## <span id="cluster1">Cluster</span>

[/cluster/kmeans.csv](./cluster/kmeans.csv)

通过代码随机生成，二维

## <span id="regression1">Regression</span>

[/regression/data.csv](./regression/data.csv)

通过代码随机生成，二维

[/regression/original20191001to20191031.xlsx](./original20191001to20191031.xlsx)

多元线性回归使用到的数据集，为**已公开**数据，可从 [http://seqbeacon.genomics.cn:443/download.html](http://seqbeacon.genomics.cn:443/download.html) 下载而得

## <span id="onehot1">onehot</span>

[/regression/onehot.csv](./regression/onehot.csv)

通过代码随机生成，三维，一维与二为需要 onehot 处理的特征

# 参考

## <span id="cluster2">Cluster</span>

### <span id="kmeans1">Kmeans</span>

* [https://healthcare.ai/step-step-k-means-clustering/](https://healthcare.ai/step-step-k-means-clustering/) 图解说明，非常棒！
* [https://blog.csdn.net/u013719780/article/details/78413770](https://blog.csdn.net/u013719780/article/details/78413770) 从中得知何时结束聚类

## <span id="onehot2">onehot</span>

* [https://hackernoon.com/what-is-one-hot-encoding-why-and-when-do-you-have-to-use-it-e3c6186d008f](https://hackernoon.com/what-is-one-hot-encoding-why-and-when-do-you-have-to-use-it-e3c6186d008f)
* [https://2-bitbio.com/2018/06/one-hot-encode-dna-sequence-using.html](https://2-bitbio.com/2018/06/one-hot-encode-dna-sequence-using.html)
* [https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/](https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/)
