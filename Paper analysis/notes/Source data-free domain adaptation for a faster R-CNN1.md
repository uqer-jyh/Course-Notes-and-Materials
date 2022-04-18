# Data-Free/2022/Pattern Recognition

## Source data-free domain adaptation for a faster R-CNN

### https://doi.org/10.1016/j.patcog.2021.108436

## 背景Background

### What is known？

- source data-free domain adaptation object detection

### What is new？

- Only unlabeled target domain data is used to optimize the source domain model so that it can work better in the target domain.
- Taking Faster R-CNN as baseline, constructing global class prototypes which will be updated in batch iteratively
- More accurate pseudo-labels are generated for training the target model for based on global class prototypes

### What are the implications?

- 研究意义/应用价值
- Achieving the state-of-the-art results in terms of accuracy compared with the Faster R-CNN model and some domain adaptive methods with source datasets.

## 实验方法Methods

### 重点描述改进或新提出的部分

### Conduct source data-free domain adaptive object detection experiments based on the stable Faster R-CNN network with VGG16 backbone.

### The source domain data is not accessed, and only the source domain model is retained.



## 实验结果Results

### 逻辑重点：这一部分实验证明了什么问题

- 研究结果
- Have a 4.4% improvement compared to the baseline.
- The prediction results of two variants in each category are better than the baseline (Source only).
- Experimental results exceed the two domain adaptive object detection methods with source domain data.

## 灵感Insights

### 第一遍读文章

- 记录不懂的知识特别是专业术语
- 对自己的研究有什么作用

### 反复

- 这篇文章的亮点是什么？
- Storytelling怎么样？
- 哪一部分比较难理解？还欠缺什么知识？