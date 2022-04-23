# 基于WordNet构建的英语词汇实体和同义词集实体知识图谱
### 抽取实体：
+ Lemma(WordNode) 
+ Synset(SynsetNode)
### 抽取关系：
+ InSynset(Lemma(WordNode), Synset(SynsetNode), InSynset)
+ IsA(Synset(SynsetNode), Synset(SynsetNode), IsA)
+ PartOf(Synset(SynsetNode), Synset(SynsetNode), PartOf)
+ Domain(Synset(SynsetNode), Synset(SynsetNode), Domain)
+ Attribute(Synset(SynsetNode), Synset(SynsetNode), Attribute)
+ Cause(Synset(SynsetNode), Synset(SynsetNode), Cause)
+ SimilarTo(Synset(SynsetNode), Synset(SynsetNode), SimilarTo)
+ Antonym(Synset(SynsetNode), Synset(SynsetNode), Antonym)
+ Entailment(Synset(SynsetNode), Synset(SynsetNode), Entailment)
### 效果预览
![](./graph.png)
### 词汇问答
![](./qa_app.png)
