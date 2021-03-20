### The dataset and code for our paper:  **_"[Cooperative Prediction Method Based on Dynamic and Static Representation for Crowdfunding][http://www.jos.org.cn/html/2020/4/5921.htm]"_** （In Chinese）



### First, the wordVectors.npy file should be combined through:

```
cat wordVectors-xa* > wordVectors.npy 
```

the review info has been concluded in the feature embeddings.

### Then, we can run the baselines or the proposed model through:

```
python ../baseline/**.py or python dscp.py
```



If this repo is helpful to you, please kindly cite our paper, thank you！

张凯, 赵洪科, 刘淇, 潘镇, 陈恩红. 基于动静态表征的众筹协同预测方法. 软件学报, 2020, 31(4): 967-980. http://www.jos.org.cn/1000-9825/5921.htm

Zhang K, Zhao HK, Liu Q, Pan Z, Chen EH. Cooperative Prediction Method Based on Dynamic and Static Representation for Crowdfunding. Journal of Software, 2020, 31(4): 967-980(in Chinese). http://www.jos.org.cn/1000-9825/5921.htm