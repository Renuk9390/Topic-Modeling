
This GitHub repository contains the data and code associated with the paper titled **"Decoding Health Informatics Patents: Investigating Topic Models for Patent Information Retrieval."**

## Abstract

Supervised large language models often struggle to provide transparency in identifying niche and interrelatable topics within a patent corpus where precise terminology is paramount. Topic models can uncover subtle themes and trends that may be overlooked by broader language models. In particular, interdisciplinary disciplines such as healthcare informatics pose substantial challenges in the efficient retrieval of pertinent information. In this context, we propose leveraging topic modeling techniques to streamline information retrieval.

**Objectives:**
1. Train a hierarchical BERTopic model to replicate the hierarchical classification of patents within the G16H (healthcare informatics) category. This entails acquiring distinct representations for all classification codes falling under G16H.
2. Assess the efficiency of different sections of patents (claims or abstracts) in pinpointing the most relevant group of documents for a given query or test application.
3. Emphasize the critical importance of streamlining the search process, focusing initially on pertinent groups or sets before narrowing down to a smaller initial document set for subsequent prior art retrieval.

The data, spanning over 70 years of G16H patents, and the corresponding code related to this work are made public to promote further research in this direction.

**Additional Explanations of Paper**
1. In light of the interdisciplinary nature encompassing informatics, communication, technology, and the medical domain, the G16H patent category emerges as the optimal dataset for exploring complexities in handling intricate patent data. Thus, our choice to focus on G16H patents is driven by the diverse and relevant landscape it represents.

## Dataset

The dataset utilized in this research is available [here](https://drive.google.com/drive/folders/1bM3BhnKEAh-faW9DJHGdnxKZbe3C9QoS?usp=sharing). Feel free to explore and leverage the data for your own research purposes.

---

*Note: Make sure to comply with the terms of use associated with the provided dataset.*
