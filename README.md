# Python在电商平台的购物评价中的分析与应用

### 部分文件说明
|文件名|说明|
|:---:|:---:|
|tm|在[淘宝天猫](https://detail.tmall.com/item.htm?spm=a230r.1.14.14.385d7868FK4F41&id=589815124915&cm_id=140105335569ed55e27b&abbucket=14&on_comment=1&sku_properties=10004:827902415;5919063:6536025)上获取的全部原始数据|
|jd|在[京东商城](https://item.jd.com/100002795957.html#none)上获取的全部原始数据|
|sn|在[苏宁易购](https://product.suning.com/0000000000/10973073658.html?safp=d488778a.13701.productWrap.2&safc=prd.3.ssdsn_pic00-1_jz&safpn=10007)上获取的全部原始数据|
|hw|在[华为商城](https://www.vmall.com/product/10086102942203.html?cid=70146)上获取的全部原始数据|
|LDA|保存的LDA模型、corpus和dictionary|
|pictures|论文当中所有的图片，包括代码生成的图片、自己画的流程图、以及截图|
|sentiment|情感词典（包括程度副词词典、否定词词典、正负面情感词词典），以及两个生成的snownlp模型|
|big_neg.txt|将小于-10分的评价数据和snownlp原始的负面评价语料结合后的总的负面评价数据|
|big_pos.txt|将等于20分的评价数据和snownlp原始的正面评价语料结合后的总的正面评价数据|
|dict.txt|将新词发现的词语和jieba原始的词典结合后的总的词典|
|neg.txt|snownlp原始的负面评价语料|
|pos.txt|snownlp原始的正面评价语料|
|select_neg.txt|将人工筛选的100条负面评价和snownlp原始的负面评价语料结合后的总的负面评价数据|
|select_pos.txt|将人工筛选的100条正面评价和snownlp原始的正面评价语料结合后的总的正面评价数据|
|sentences.txt|分别将每个人的评论正文和追评正文相加而生成的总的评价数据|
|stoplist.txt|jieba中原始的停用词|
|全部数据.csv|将淘宝天猫、京东商城、苏宁易购和华为商城的全部数据合并后生成的csv文件|
|清洗后的数据.csv|将全部数据经过数据预处理后生成的csv文件|
|requirements.txt|当时所使用的Python第三方库及其对应的版本号|
