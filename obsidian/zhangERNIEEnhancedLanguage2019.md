# ERNIE: Enhanced Language Representation with Informative Entities

![[zhangERNIEEnhancedLanguage2019-zotero#Metadata]]

Other files:

- Mdnotes File Name: [[zhangERNIEEnhancedLanguage2019]]
- Metadata File Name: [[zhangERNIEEnhancedLanguage2019-zotero]]

## Zotero links

- [Local library](zotero://select/items/1_WQSZAQXY)
- [Cloud library](http://zotero.org/users/8603990/items/WQSZAQXY)

|  **Item**    |  **Content**                                                                                                                                                                                                                         |
|:-------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  Motivation  |  1. 传统的BM缺乏显式的知识嵌入<div>2. 在BM中引入知识可以增强模型对于语义的理解</div><div>3. 在BM中引入知识可以在一些KG任务中取得更好地性能:Entity Typing/Relation Classification</div>                                                                                                   |
|  Innovation  |  提出了新的训练目标,在一般的预训练目标(MLM,NSP)基础上,加入了对于实体关系embedding的预测                                                                                                                                                                               |
|  Method      |  ![[Pasted image 20221102170802.png]]                                                                                                                                      <div>**知识embedding融合方式**:Embedding Concat + FC</div>      |
|  Ref         |                                                                                                                                                                                                                                      |
|  Conclusion  | 论文设计了一种BM融合实体知识的方法,通过加入新的预训练目标以及引入新的K-Encoder融合上下文与实体Embedding,从而在自然语言理解以及KG任务上都取得更优的性能.                                                                                                                                             |

## Other
