# Salient Object Ranking

A curated list of awesome resources for salient object ranking (SOR). We will keep updating it.

:heavy_exclamation_mark:Updated 2024-06-08.

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
|     2024   |  CVPR   | Advancing Saliency Ranking with Human Fixations: Dataset, Models and Benchmarks | Paper/Code
|    2024    |   CVPR  | Domain Separation Graph Neural Networks for Saliency Object Ranking  | Paper/Code 
|    2024    |   AAAI  | SeqRank: Sequential Ranking of Salient Objectsg  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27964/27947)/[Code](https://github.com/guanhuankang/SeqRank) 
|    2024    |   ECCV  | PoseSOR: Human Pose Can Guide Our Attention | [Paper](https://www.cs.cityu.edu.hk/~rynson/papers/eccv24.pdf)/[Code](https://github.com/guanhuankang/ECCV24PoseSOR)

## Video-SOR
| **Year** | **Pub.** | **Title**              | **Links**                                                    |
| :------: | :------- | :----------------------------------------------------------- | :------------------------------------------------------------ |
|     2019   |  ACMMM   | Ranking Video Salient Object Detection  | [Paper](https://dl.acm.org/doi/pdf/10.1145/3343031.3350882)/[Code](https://github.com/XinyuYanTJU/RVSOD) 
|     2022   | ArXiv | Rethinking Video Salient Object Ranking  | [Paper](https://arxiv.org/pdf/2203.17257)/Code


<!-- ## Metric
|        |     |  | [Paper]()/[Code]()  -->

## Application
| **Year** | **Pub.** | **Title**              | **Links**                                                    |
| :------: | :------- | :----------------------------------------------------------- |:------------------------------------------------------------ |
| 2011 | WACV | Saliency retargeting: An approach to enhance image aesthetics | [Paper](https://d1wqtxts1xzle7.cloudfront.net/86911875/saliency_retargeting_wacv2011-libre.pdf?1654226908=&response-content-disposition=inline%3B+filename%3DSaliency_retargeting_An_approach_to_enha.pdf&Expires=1717820241&Signature=G7p-ZGzax2U07jyE-bQqQwPqkz7ZJvAvydU71l8g9HSBvPeQZsccA6CSjAYwJ5YcaxkiFj2dJUdHk6sVRKv8sxe13EQFOqU8e8t~MMeb2gpZo8DhEStXucdBTYYpHVaOUpvfhSFhC7~ufWVXgfFnM8MfLFvhX8HtBpHfq3cHfab-wzOS8b9GrT0SQ95Y8LKyOeD8ik3NryoWX~P545jw5m5QNxneKZd9cerZa-lnscObnudsqy~GJFGNJhkjC1hoGlZu5Ake8DPX9hnSLatdbEXSqmCzQUN-POJgwvlDY-SZ6lnR9cYEKTgG9FW1-DLkHZSjNC3mgSotA3SIPfp3vw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)/Code
|   2024  |   IJCV  | IRNet-RS: image retargeting network via relative saliency | [Paper](https://link.springer.com/article/10.1007/s00521-023-09258-6)/Code


## Reference
[Salient Object Detection](https://github.com/visionxiang/awesome-salient-object-detection)

