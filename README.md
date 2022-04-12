# medical_text_information_retrieval_system

本项目致力于构建对于医疗文本的信息检索系统。

（1）查询文本为实际应用领域中的医疗文本，未经预处理，包含大量专有名词及医疗术语

（2）系统应用倒排索引，对检索信息进行预先缓存初始化，减少查询开销，查询时间为毫秒级别。

（3）引入医学辞典，提高查询精度。

（4）查询函数满足关键词查询，例：q='条状钙化影'

（5）查询函数满足布尔条件查询，例：q = '(左肺 or 右肺) and 间质性'

（6）根据bm25算法对查询结果进行相关度衡量，并依照相关度得分排序


本项目文件包括

（1）代码文件：medical_text_retrieval_system.ipynb

（2）源数据文件：data/medical_text_data.csv

（3）医学辞典：dictionary/chinese_medical_words-master/...

（4）用户自定义字典：dictionary/add_dict.txt
