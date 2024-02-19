
This GitHub repository contains the data and code associated with the paper titled **"Decoding Health Informatics Patents: Investigating Topic Models for Patent Information Retrieval."**
For any queries, please reach out to:

RenukSwamy Chikkamath  
Email: [renukswamy.chikkamath@hm.edu](mailto:renukswamy.chikkamath@hm.edu)

## Abstract

Supervised large language models often struggle to provide transparency in identifying niche and interrelatable topics within a patent corpus where precise terminology is paramount. Topic models can uncover subtle themes and trends that may be overlooked by broader language models. In particular, interdisciplinary disciplines such as healthcare informatics pose substantial challenges in the efficient retrieval of pertinent information. In this context, we propose leveraging topic modeling techniques to streamline information retrieval.

**Objectives:**
1. Train a hierarchical BERTopic model to replicate the hierarchical classification of patents within the G16H (healthcare informatics) category. This entails acquiring distinct representations for all classification codes falling under G16H.
2. Assess the efficiency of different sections of patents (claims or abstracts) in pinpointing the most relevant group of documents for a given query or test application.
3. Emphasize the critical importance of streamlining the search process, focusing initially on pertinent groups or sets before narrowing down to a smaller initial document set for subsequent prior art retrieval.

The data, spanning over 70 years of G16H patents, and the corresponding code related to this work are made public to promote further research in this direction.

**Additional Explanations of Paper**
1. In light of the interdisciplinary nature encompassing informatics, communication, technology, and the medical domain, the G16H patent category emerges as the optimal dataset for exploring complexities in handling intricate patent data. Thus, our choice to focus on G16H patents is driven by the diverse and relevant landscape it represents.
2. In general, Deep Learning and Large Language Models lack the ability to explain why a specific class is predicted (e.g., in a classification setting) or why a particular document is considered relevant (e.g., in an information retrieval setting, such as AI-based search engines). This inherent limitation contributes significantly to the black-box nature of AI models, hindering transparency. In contrast, topic models offer transparency by revealing specific words or phrases that serve as reasons for selecting a relevant document in an information retrieval setting. Further insights into the challenges associated with using Large Language Models (LLMs) or Deep Learning (DL) models for search are elaborated in [1,2,3].
3. (**To be added**) References (code and details) demonstrating the investigation of the hierarchical topic modeling capabilities of BERTopic for showcasing the hierarchical classification of patents within the G16H category.
4. Notable differences in terms of training diverse topic models using patent abstracts and claims, along with their efficiencies when used in information retrieval as a sole strategy, are explained in detail in Section 5 (Results and Discussion) of the paper.
5. Questions such as the following mostly pertain to future work in our paper, which is related to this repository and can also be considered as some of the open research areas for the empirical investigations presented in our paper:

i) 'How easily can the proposed topic modeling techniques be integrated into existing patent search systems, and what considerations should be taken into account for practical implementation?'
OR
ii) 'Are there plans for collaboration with other researchers or institutions in further exploring the applications and extensions of the proposed topic modeling techniques in patent analysis or other domains?'

## Dataset

The dataset utilized in this research is available [here](https://drive.google.com/drive/folders/1bM3BhnKEAh-faW9DJHGdnxKZbe3C9QoS?usp=sharing). Feel free to explore and leverage the data for your own research purposes.

### References
1. Chikkamath, Renukswamy, Deepak Rastogi, Mahesh Maan, and Markus Endres. "Is your search query well-formed? A natural query understanding for patent prior art search." World Patent Information 76 (2024): 102254.
2. Vowinckel, Konrad, and Volker D. Hähnke. "SEARCHFORMER: Semantic patent embeddings by siamese transformers for prior art search." World Patent Information 73 (2023): 102192.
3. Chikkamath, Renukswamy, Rana Fassahat Ali, Christoph Hewel, and Markus Endres. "Explainable Artificial Intelligence for Highlighting and Searching in Patent Text." (2023).PatentSemTech'23: 4th Workshop on Patent Text Mining and Semantic Technologies, colocated with the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval, July 27th, 2023, Taipei, Taiwan.
---

*Note: Make sure to comply with the terms of use associated with the provided dataset.*
