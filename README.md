# Graph-Pegasus

we introduce Graph-Pegasus, a graph-infused Transformer framework that combines a Legal Entity-Relation Graph (LERG) with a Pegasus-based abstractive summarization model. LERG explicitly models entities, phrases, statutes, and case citations as nodes, including sequential, semantic, and discourse relationships between sentences. A Graph Transformer Network is utilized to fuse the graph representations with the Pegasus encoder, allowing the model to employ structural and semantic context to generate better summary outputs.
Experiments with a curated dataset of Indian Supreme Court cases demonstrate how this approach outperforms the baseline transformer and large language models in ROUGE, METEOR, BERTScore, and Perplexity scores. The suggested methodology emphasizes the benefits of combining structured legal knowledge with pretrained language models, offering an achievable way out for efficient and accurate legal text summarizing.

The dataset used in this research can be found in https://www.kaggle.com/datasets/pawank1999/indian-supreme-court-legal-judgments
