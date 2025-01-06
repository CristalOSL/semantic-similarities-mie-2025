# Computing Semantic Similarities with Optimized BERT Models: The Case of the French Medical Language

## Authors
- Idriss JAIRI (https://orcid.org/0000-0003-2502-9283)
- Hayfa ZGAYA-BIAU (https://orcid.org/0000-0002-7761-7725)
- Natalia GRABAR (https://orcid.org/0000-0002-0237-4554)

## Abstract
Semantic similarity aims to assess semantic correspondence between pieces of text. This is an important Natural Language Processing (NLP) application, as it enables better understanding and interpretation of textual data, improving various downstream tasks. In comparison to Large Language Models (LLMs), which are versatile and excel at text generation tasks, Bidirectional Encoder Representations from Transformers (BERT) models are widely used for text analysis and identifying similarities between language units. Yet, in the modern AI world, with the development of more advanced models, researchers face challenges due to the sheer model size and computational demands. Deploying such models adds challenges related to energy consumption, memory usage, and latency. To address these challenges, emerging trends propose model optimization techniques, significantly reducing memory usage and speeding up inference. In this work, we introduce a method for semantic similarity, leveraging open-source Microsoft Olive tool to search for optimal optimizations, followed by a dynamic quantization process. We evaluate the models on the Text Mining Challenge DEFT 2020. We slightly improve the performance metrics while simultaneously attaining an average inference speed-up of 20x and reducing memory usage by approximately 70%.
