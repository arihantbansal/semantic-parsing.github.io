---
layout: publication
title: "Spider: A Large-Scale Human-Labeled Dataset for Complex and Cross-Domain Semantic Parsing and Text-to-SQL Task"
authors: Tao Yu, Rui Zhang, Kai Yang, Michihiro Yasunaga, Dongxu Wang, Zifan Li, James Ma, Irene Li, Qingning Yao, Shanelle Roman, Zilin Zhang, Dragomir Radev
conference: EMNLP
year: 2018
bibkey: yu2018spider
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/1809.08887"}
   - {name: "PDF", url: "https://aclanthology.org/2021.naacl-main.33.pdf"}
   - {name: "Website", url: "https://yale-lily.github.io/spider"}
tags: ["sql", "cross-domain", "dataset"]
---
We present Spider, a large-scale, complex and cross-domain semantic parsing and text-to-SQL dataset annotated by 11 college students. It consists of 10,181 questions and 5,693 unique complex SQL queries on 200 databases with multiple tables, covering 138 different domains. We define a new complex and cross-domain semantic parsing and text-to-SQL task where different complex SQL queries and databases appear in train and test sets. In this way, the task requires the model to generalize well to both new SQL queries and new database schemas. Spider is distinct from most of the previous semantic parsing tasks because they all use a single database and the exact same programs in the train set and the test set. We experiment with various state-of-the-art models and the best model achieves only 12.4% exact matching accuracy on a database split setting. This shows that Spider presents a strong challenge for future research. Our dataset and task are publicly available at this URL: https://yale-lily.github.io/spider
