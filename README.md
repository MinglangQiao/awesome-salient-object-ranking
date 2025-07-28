# Salient Object Ranking

A curated list of awesome resources for salient object ranking (SOR). We will keep updating it.

:heavy_exclamation_mark:Updated 2024-11-29.

## Content:
- [Salient Object Ranking](#salient-object-ranking)
  - [Content:](#content)
  - [Image-SOR](#image-sor)
  - [Video-SOR](#video-sor)
  - [Application](#application)
  - [Reference](#reference)

<!-- ## Database

| **Year** | **Pub.** | **Title**                                      | **Links**                                              |
| :------: | :------: | :--------------------------------------- | :----------------------------------------------------------- |
|   x   |   x    | x | x | -->

## Image-SOR

| **Year** | **Pub.** | **Title**              | **Links**                                                    |
| :------: | :------- | :----------------------------------------------------------- | :------------------------------------------------------------ |
|   2018  | CVPR | Revisiting Salient Object Detection: Simultaneous Detection, Ranking, and Subitizing of Multiple Salient Objects | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Islam_Revisiting_Salient_Object_CVPR_2018_paper.pdf)/[Code1](https://github.com/islamamirul/rsdnet), [Code2](https://github.com/MinglangQiao/pytorch-rsdnet-sor?tab=readme-ov-file)
|   2019  | TPAMI | Relative Saliency and Ranking: Models, Metrics, Data, and Benchmarks | [Paper](https://arxiv.org/pdf/1810.02426)/Code
|   2020  | CVPR | Inferring attention shift ranks of objects for image saliency | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Siris_Inferring_Attention_Shift_Ranks_of_Objects_for_Image_Saliency_CVPR_2020_paper.pdf)/[Code](https://github.com/SirisAvishek/Attention_Shift_Ranks)
|    2021 | ICCV    |   Salient object ranking with position-preserved attention  | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Fang_Salient_Object_Ranking_With_Position-Preserved_Attention_ICCV_2021_paper.pdf)/[Code](https://github.com/EricFH/SOR) 
|     2021   |  TPAMI   | Instance-level relative saliency ranking with graph reasoning | [Paper](https://arxiv.org/pdf/2107.03824)/[Code](https://github.com/dragonlee258079/Saliency-Ranking) 
|     2022   | CVPR | Bidirectional object-context prioritization learning for saliency ranking   | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Tian_Bi-Directional_Object-Context_Prioritization_Learning_for_Saliency_Ranking_CVPR_2022_paper.pdf)/[Code](https://github.com/GrassBro/OCOR) 
|  2023   | ACMMM   |  Partitioned Saliency Ranking with Dense Pyramid Transformers   | [Paper](https://arxiv.org/pdf/2308.00236)/[Code](https://github.com/ssecv/PSR) 
|   2023     |  TIP   | Rethinking Object Saliency Ranking: A Novel Whole-Flow Processing Paradigm | [Paper](https://www.researchgate.net/profile/Mengke-Song-2/publication/376579322_Rethinking_Object_Saliency_Ranking_A_Novel_Whole-flow_Processing_Paradigm/links/658957dc6f6e450f19a181a0/Rethinking-Object-Saliency-Ranking-A-Novel-Whole-Flow-Processing-Paradigm.pdf)/[Code](https://github.com/mengkesong/saliency-ranking-paradigm) 
|     2023   |   PR  | RGB-D salient object ranking based on depth stack and truth stack for complex indoor scenes | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320322007300)/Code
|     2024   |   TPAMI  | HyperSOR: Context-aware Graph Hypernetwork for Salient Object Ranking | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10443257)/[Code](https://github.com/MinglangQiao/SalSOD) 
|     2024   |  CVPR   | Advancing Saliency Ranking with Human Fixations: Dataset, Models and Benchmarks | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Deng_Advancing_Saliency_Ranking_with_Human_Fixations_Dataset_Models_and_Benchmarks_CVPR_2024_paper.pdf)/[Code](https://github.com/EricDengbowen/QAGNet)
|    2024    |   CVPR  | Domain Separation Graph Neural Networks for Saliency Object Ranking  | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_Domain_Separation_Graph_Neural_Networks_for_Saliency_Object_Ranking_CVPR_2024_paper.pdf)/[Code](https://github.com/Wu-ZJ/DSGNN) 
|    2024    |   AAAI  | SeqRank: Sequential Ranking of Salient Objectsg  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27964/27947)/[Code](https://github.com/guanhuankang/SeqRank) 
|    2024    |   ECCV  | PoseSOR: Human Pose Can Guide Our Attention | [Paper](https://www.cs.cityu.edu.hk/~rynson/papers/eccv24.pdf)/[Code](https://github.com/guanhuankang/ECCV24PoseSOR)
|    2024    |   arXiv | CaRDiff: Video Salient Object Ranking Chain of Thought Reasoning for Saliency Prediction with Diffusion | [Paper](https://arxiv.org/pdf/2408.12009)
|    2024    |   ECCV    | PoseSOR: Human Pose Can Guide Our Attention | [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02792.pdf)/[Code](https://github.com/guanhuankang/ECCV24PoseSOR)
|    2024    |  arXiv | Leverage Task Context for Object Affordance Ranking | [Paper](https://arxiv.org/pdf/2411.16082)
|    2024    |  IJCV  | Inferring Attention Shifts for Salient Instance Ranking | [Paper](https://link.springer.com/article/10.1007/s11263-023-01906-7)
|  2024  |  IVCI  | Category-based depth incorporation for salient object ranking | [Paper](https://pdf.sciencedirectassets.com/272324/1-s2.0-S1047320324X00048/1-s2.0-S1047320324001202/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIHAVgWSM6%2FA4aHcqY2l49VFzGalmKh7BUy5gMgjtsxZyAiEA9Ctyosd%2FhooNM35ajfWOgVM17%2BtIDQUeBnc5mnOzuS0qvAUInv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDNHjtrDd1RfAbVoiEiqQBToueRmjxYDdGqH8wv163%2B61a7tSBozDhEicXEKOOgrBWSm6H5wiHCw%2FAWEr%2FQv9O4Fp%2BvT69%2BVw9D5NQ9hmUn1NAE3xk9j7CQMarvSuLC8E9hx%2BrK%2BM0sxhOqzy%2BEaytONEHEcshdP5ll8yW1pSWJJo8buEnCXbtXo0iHv%2FRw%2BVzgbRF1l%2FCPdsgE05VO3GSfoPUHXWIMk0djpEnwvR5jSQitgo6R6jEZVFd1iE774eLkfcoOV1q4%2B8hmng4AhpjU%2F4h1e%2FUw2FdRe%2FCO%2BxeEbxbHMBeSgRKZ%2Bbf3397TSNkWvPZf3%2BbTwnwtfx93dTKC8LxfFPTi0VzqYtwNsYrYlcBUxt8JEvAPlehg%2FHIJYPEXhgJJPV5cJ%2FlV%2BrsgQA88rlPlRUUcZx2QumAjSCla954c2pNmE9wKYXhm1aTf15spuQd8myKYWJoEKhQIgDh8NstiMFcwo8kN9mHX2KHMQK6KyXhNNeDvVBl9S10Vzco9NTBU%2Fkm6RuIVCMt4%2B7iqfKrG2k8vZhvLGNMEhtBwRVec50Xto9W7dGuCaPBMMnNZ2cR7J6PkRnoPNNogaa2Dk5JJkPkyAekjqcmFRLHkbzbGT4esiSe4RJAntAwaxHCwUmMJ8L0UuRUeiH5a5JTB%2FLreTKyClXMt4twqba8ooSxcajkxVF7yBG21%2FKt2U8wKw0tDgeEk3YTTIoVTDuvFJOg1rzoM9Fyoe4ArZlbPH9S3Wpw4zx0flM%2BFcvjFDQ9nTScDJjiGG5uSaMU5G0Aj3idC6yyXrTtRADvuB7o5mDSJTQdjBkzHCRW20D7h0CwLRxShfhDbaKWq6w3%2FLOrMe1jofFk8HA9x7s2NGuD7QWYeO5fDybyOSf7x6BBFAnMMCy5LoGOrEBfLxXnOJIsQ5m1GzO4l7DDGIY7vx1Xp2HG7W3ln5%2F8XA1YKikTenCVeHIj9GabC6Yj3kEomASelmTZjDprvbJgBaJ2sfagWL25MDPTfM3rR5ZJRtkoMpkFp1wnw0GNmWWxydy2aWlDEkuZbyJ17eZj8BgGqvrvPzmYLlARdj8ONmxciHFSKGFTG3QiGEYBj%2BCXwcOC8B1iOp1W8574lKy4uwmVuQ1tswLYkqY%2F3%2F79PzE&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20241211T062739Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYVWN2CYK2%2F20241211%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a17b6f7ed1e6bc66d375e03727cb2ba383768e72cc36c430275d045b5cd952db&hash=91dc029cbf7d40ccd3de2ce5a14d86c03f1776455cd9705cb660c4317d17d9a5&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1047320324001202&tid=spdf-615bd5b9-f852-4271-b944-018416646237&sid=67e4665955dd50408b28ff90049e55cc5097gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=050e5e025651595d0554&rr=8f0368f70f8e8b2f&cc=cn&kca=eyJrZXkiOiJ6MFM2Zmo3SDNpbm1OeDVWVjFqZUJnM1RuUmJZbVUwVjFvV3dlS0RPOWlIdVN5SjlzQ0F1Q3E1M2tCMm93a01Ddi9aWFJObEtsMndweENTWTF2NW81WC93R0p0VzNiRlRlQkR2YTlaMzlPZEJQaVVFU1Y4Q1lmMkdXdDdMVmw5d1hlVWF5U1EyNm9vY1cxWi90alFrZUhXWWthQWFlM01PeVNsekFkZ3ZSTTJTckYwWWtRPT0iLCJpdiI6Ijk5YjA1OGIwZGI0YmIwYWUwY2M2OGI4YWZhMmExMWE2In0=_1733898476093)
| 2025 | CVPR | Language-Guided Salient Object Ranking | [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Liu_Language-Guided_Salient_Object_Ranking_CVPR_2025_paper.pdf)
| 2025 | AAAI | Fine-Grained Perception in Panoramic Scenes: A Novel Task, Dataset, and Method for Object Importance Ranking | [Paper](https://ojs.aaai.org/index.php/AAAI/article/download/32746/34901)

## Video-SOR
| **Year** | **Pub.** | **Title**              | **Links**                                                    |
| :------: | :------- | :----------------------------------------------------------- | :------------------------------------------------------------ |
|     2019   |  ACMMM   | Ranking Video Salient Object Detection  | [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3350882)/[Code](https://github.com/XinyuYanTJU/RVSOD) 
|     2022   | ArXiv | Rethinking Video Salient Object Ranking  | [Paper](https://arxiv.org/pdf/2203.17257)/Code
|    2024    |   ACMMM    | Instance-Level Panoramic Audio-Visual Saliency Detection and Ranking | [Paper](https://dl.acm.org/doi/pdf/10.1145/3664647.3681070)/[Code](https://github.com/ruohaoguo/pavsodr)
|    2024    |   NeurIPS | A Motion-aware Spatio-temporal Graph for Video Salient Object Ranking | [Paper](https://openreview.net/pdf?id=VUBtAcQN44)   


<!-- ## Metric
|        |     |  | [Paper]()/[Code]()  -->

## Application
| **Year** | **Pub.** | **Title**              | **Links**                                                    |
| :------: | :------- | :----------------------------------------------------------- |:------------------------------------------------------------ |
| 2011 | WACV | Saliency retargeting: An approach to enhance image aesthetics | [Paper](https://d1wqtxts1xzle7.cloudfront.net/86911875/saliency_retargeting_wacv2011-libre.pdf?1654226908=&response-content-disposition=inline%3B+filename%3DSaliency_retargeting_An_approach_to_enha.pdf&Expires=1717820241&Signature=G7p-ZGzax2U07jyE-bQqQwPqkz7ZJvAvydU71l8g9HSBvPeQZsccA6CSjAYwJ5YcaxkiFj2dJUdHk6sVRKv8sxe13EQFOqU8e8t~MMeb2gpZo8DhEStXucdBTYYpHVaOUpvfhSFhC7~ufWVXgfFnM8MfLFvhX8HtBpHfq3cHfab-wzOS8b9GrT0SQ95Y8LKyOeD8ik3NryoWX~P545jw5m5QNxneKZd9cerZa-lnscObnudsqy~GJFGNJhkjC1hoGlZu5Ake8DPX9hnSLatdbEXSqmCzQUN-POJgwvlDY-SZ6lnR9cYEKTgG9FW1-DLkHZSjNC3mgSotA3SIPfp3vw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)/Code
|   2024  |   IJCV  | IRNet-RS: image retargeting network via relative saliency | [Paper](https://link.springer.com/article/10.1007/s00521-023-09258-6)/Code


## Reference
[Salient Object Detection](https://github.com/visionxiang/awesome-salient-object-detection)

