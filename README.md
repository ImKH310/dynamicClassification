## Domain-embedding-enhanced dynamic text classification
### 'Dynamic building defect categorization through enhanced unsupervised text classification with domain-specific corpus embedding methods'
This study proposes two methods to enhance unsupervised text classification for domain-specific non-English text using improved domain corpus embedding: 1) weighted embedding-based anchor word clustering (wean-Clustering), and 2) cosine-similarity-based classification using a defect corpus that is vectorized by fine-tuned pre-trained language models (sim-Classification-ftPLM). The proposed methods were tested on 40,765 Korean building defect complaints and achieved F1 scores of 89.12% and 84.66% respectively. 

Paper (under review in Automation in Construction) 


### Requirements

    python >= 3.6
    pandas, numpy, gensim, scikit-learn, scipy, sklearn, tqdm, re, pickle
    torch, sentence transformer,  
    MeCab, konlpy
    
    All experiments were conducted on a Windows 10 system with an RTX 3090 GPU and 24 GB of memory using Python 3.
    
### Download pre-trained Word2Vec 

Please download pre-trained Word2Vec (30+ multilingual support) https://github.com/Kyubyong/wordvectors 

### Anchored-CorEx for the wean-Clustering

The original excution code of anchored-CorEx is available here: 
https://github.com/gregversteeg/CorEx 


