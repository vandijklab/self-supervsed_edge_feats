## self-supervised_edge_feats

Code and data for Sehanobish A*, Ravindra NG*, van Dijk D. "Gaining insight into SARS-CoV-2 Infection and COVID-19 Severity using Self-supervised Edge Features and Graph Neural Networks." To appear at AAAI' 21. * Co-first authors

### Summary

A molecular and cellular understanding of how SARS-CoV-2 variably infects and causes severe COVID-19 remains a bottleneck in developing interventions to end the pandemic. We sought to use deep learning to study the biology of SARS-CoV-2 infection and COVID-19 severity by identifying transcriptomic patterns and cell types associated with SARS-CoV-2 infection and COVID-19 severity. To do this, we developed a new approach to generating self-supervised edge features. We propose a model that builds on Graph Attention Networks (GAT), creates edge features using self-supervised learning, and ingests these edge features via a Set Transformer. This model achieves significant improvements in predicting the disease state of individual cells, given their transcriptome. We apply our model to single-cell RNA sequencing datasets of SARS-CoV-2 infected lung organoids and bronchoalveolar lavage fluid samples of patients with COVID-19, achieving state-of-the-art performance on both datasets with our model. We then borrow from the field of explainable AI (XAI) to identify the features (genes) and cell types that discriminate bystander vs. infected cells across time and moderate vs. severe COVID-19 disease. To the best of our knowledge, this represents the first application of deep learning to identifying the molecular and cellular determinants of SARS-CoV-2 infection and COVID-19 severity using single-cell omics data.




----

### Data availability


### Citation
* Pre-print: https://arxiv.org/abs/2006.12971
``` 
@article{Sehanobish_Ravindra_edge_feats_2021, 
    title=Gaining insight into SARS-CoV-2 Infection and COVID-19 Severity using Self-supervised Edge Features and Graph Neural Networks}, 
    volume={35}, 
    url={TBD}, 
    DOI={TBD}, 
    number={04}, 
    journal={Proceedings of the AAAI Conference on Artificial Intelligence}, 
    author={Sehanobish, Arijit and Ravindra, Neal and van Dijk, David}, 
    year={2021}, 
    month={Apr}, 
    pages={TBD}}
```
