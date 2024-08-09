# R2S100K: Road-Region Segmentation Dataset For Semi-Supervised Autonomous Driving in the Wild 
[Muhammad Atif Butt](https://scholar.google.com/citations?user=vf7PeaoAAAAJ&hl=en), [Hassan Ali](https://scholar.google.com/citations?user=MhiaZiQAAAAJ&hl=en), [Adnan Qayyum](https://scholar.google.com/citations?user=keWNlTIAAAAJ&hl=en),  [Waqas Sultani](https://scholar.google.com/citations?user=SqcjV8EAAAAJ&hl=en), [Ala Al-Fuqaha](https://scholar.google.com/citations?user=IKnfU2kAAAAJ&hl=en), and [Junaid Qadir](https://scholar.google.com/citations?user=EdPPQToAAAAJ&hl=en)
[[arXiv](https://arxiv.org/abs/2308.06393)] [[Project](https://r2s100k.github.io/)]

## [Accepted for Publication in IJCV 2024]

![teaser](assets/pipeline-1_.jpg)

***TL;DB*** Our Efficient Data Sampling (EDS) based self-training framework. Firstly, raw data samples are clustered based on similarity in road classes among image encodings — generated by an encoder. Then, a small subset is uniformly formed from all clusters for annotation to train the teacher model. After training, pseudo-labels of the unlabeled set are generated using the
teacher model, and the student model is trained on real and pseudo-labeled sets to achieve better generalization.
