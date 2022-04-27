# 豆瓣电影知识图谱

## 文件说明
>+ `preprocess.ipynb`预处理爬取的txt格式电影数据，规范化
>+ `movie_kb.ipynb`项目核心文件，txt格式文本中，抽取信息存入mysql，导出csv，映射实体及属性。导入到Neo4j（ongdb）生成图谱。

 中间经过Mysql，纯粹属于Mysql练手，play！
## 效果预览
>![](./graph.png)
