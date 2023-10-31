This is the official repository for our ACL 2023 Findings paper: [Transitioning from benchmarks to a real-world case of information-seeking in Scientific Publications](https://aclanthology.org/2023.findings-acl.68/).

This dataset presents a practical case study where an expert in immunology seeks to study the effects of vita- min B on human health. A corpus of candidate papers was retrieved from PubMed with the following query: ("vitamin B"[Title/Abstract]) AND (health[Title/Abstract] OR growth[Title/Abstract]), which resulted in 1811 papers (December 2022 search results), out of which the expert identified 598 relevant documents (33%). Relevance judgement was carried out in two steps: 1. Search on title relevance: if a title is obviously out of scope, the expert does not investigate the abstract. Similarly, if the title is evidently in scope, the abstract is not judged. 2. Search on abstract relevance: the expert reads in detail and identifies the type of study that was carried out. More details about the dataset creation can be found in the datasheet. 

This is a dataset publicly available for the community. If you happen to use it, please cite the following work: 
```bibtex
@inproceedings{tahri-etal-2023-transitioning,
    title = "Transitioning from benchmarks to a real-world case of information-seeking in Scientific Publications",
    author = "Tahri, Chyrine  and
      Bochnakian, Aurore  and
      Haouat, Patrick  and
      Tannier, Xavier",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2023",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-acl.68",
    doi = "10.18653/v1/2023.findings-acl.68",
    pages = "1066--1076"
}



