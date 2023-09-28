# awesome-MIM
Reading list for research topics in Masked Image Modeling(MIM).

We list the most popular methods for MIM, if we missed something, please submit a request.
(Note: We show the date the first edition of the paper was submitted to arxiv, but the link to the paper may be up to date.)


## Backbone models.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2020-xx-xx(maybe 2019)|iGPT|ICML 2020|[Generative Pretraining from Pixels](http://proceedings.mlr.press/v119/chen20s/chen20s.pdf)|[iGPT](https://github.com/openai/image-gpt)
2020-10-22|ViT|ICLR 2021 (Oral)|[An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)|[ViT](https://github.com/google-research/vision_transformer)
2021-04-08|SiT|Arxiv 2021|[SiT: Self-supervised vIsion Transformer](https://arxiv.org/pdf/2104.03602.pdf)|None
2021-06-10|MST|NeurIPS 2021|[MST: Masked Self-Supervised Transformer for Visual Representation](https://arxiv.org/pdf/2106.05656.pdf)|None
2021-06-14|BEiT|ICLR 2022 (Oral)|[BEiT: BERT Pre-Training of Image Transformers](https://arxiv.org/abs/2106.08254)|[BEiT](https://github.com/microsoft/unilm/tree/master/beit)
2021-11-11|MAE|Arxiv 2021|[Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/pdf/2111.06377.pdf)|[MAE](https://github.com/facebookresearch/mae)
2021-11-15|iBoT|ICLR 2022|[iBOT: Image BERT Pre-Training with Online Tokenizer](https://arxiv.org/pdf/2111.07832.pdf)|[iBoT](https://github.com/bytedance/ibot)
2021-11-18|SimMIM|Arxiv 2021|[SimMIM: A Simple Framework for Masked Image Modeling](https://arxiv.org/pdf/2111.09886.pdf)|[SimMIM](https://github.com/microsoft/SimMIM)
2021-11-24|PeCo|Arxiv 2021|[PeCo: Perceptual Codebook for BERT Pre-training of Vision Transformers](https://arxiv.org/pdf/2111.12710.pdf)|None
2021-11-30|MC-SSL0.0|Arxiv 2021|[MC-SSL0.0: Towards Multi-Concept Self-Supervised Learning](https://arxiv.org/pdf/2111.15340.pdf)|None
2021-12-16|MaskFeat|Arxiv 2021|[Masked Feature Prediction for Self-Supervised Visual Pre-Training](https://arxiv.org/pdf/2112.09133.pdf)|None
2021-12-20|SplitMask|Arxiv 2021|[Are Large-scale Datasets Necessary for Self-Supervised Pre-training?](https://arxiv.org/pdf/2112.10740.pdf)|None
2022-01-31|ADIOS|Arxiv 2022|[Adversarial Masking for Self-Supervised Learning](https://arxiv.org/pdf/2201.13100.pdf)|None
2022-02-07|CAE|Arxiv 2022|[Context Autoencoder for Self-Supervised Representation Learning](https://arxiv.org/pdf/2202.03026.pdf)|[CAE](https://github.com/lxtGH/CAE)
2022-02-07|CIM|Arxiv 2022|[Corrupted Image Modeling for Self-Supervised Visual Pre-Training](https://arxiv.org/pdf/2202.03382.pdf)|None
2022-03-10|MVP|Arxiv 2022|[MVP: Multimodality-guided Visual Pre-training](https://arxiv.org/pdf/2203.05175.pdf)|None
2022-03-23|AttMask|ECCV 2022|[What to Hide from Your Students: Attention-Guided Masked Image Modeling](https://arxiv.org/pdf/2203.12719.pdf)|[AttMask](https://github.com/gkakogeorgiou/attmask)
2022-03-29|mc-BEiT|Arxiv 2022|[mc-BEiT: Multi-choice Discretization for Image BERT Pre-training](https://arxiv.org/pdf/2203.15371.pdf)|None
2022-04-18|Ge2-AE|Arxiv 2022|[The Devil is in the Frequency: Geminated Gestalt Autoencoder for Self-Supervised Visual Pre-Training](https://arxiv.org/pdf/2204.08227.pdf)|None
2022-05-08|MCMAE|NeurIPS 2022|[MCMAE: Masked Convolution Meets Masked Autoencoders](https://arxiv.org/pdf/2205.03892.pdf)|[MCMAE](https://github.com/alpha-vl/convmae)
2022-05-20|UM-MAE|Arxiv 2022|[Uniform Masking: Enabling MAE Pre-training for Pyramid-based Vision Transformers with Locality](https://arxiv.org/pdf/2205.10063.pdf)|[UM-MAE](https://github.com/implus/UM-MAE)
2022-05-26|GreenMIM|Arxiv 2022|[Green Hierarchical Vision Transformer for Masked Image Modeling](https://arxiv.org/pdf/2205.13515.pdf)|[GreenMIM](https://github.com/LayneH/GreenMIM)
2022-05-26|MixMIM|Arxiv 2022|[MixMIM: Mixed and Masked Image Modeling for Efficient Visual Representation Learning](https://arxiv.org/pdf/2205.13137.pdf)|[Code is Opening](https://github.com/Sense-X/MixMIM)
2022-05-28|SupMAE|Arxiv 2022|[SupMAE: Supervised Masked Autoencoders Are Efficient Vision Learners](https://arxiv.org/pdf/2205.14540.pdf)|[SupMAE](https://github.com/cmu-enyac/supmae)
2022-05-30|HiViT|Arxiv 2022|[HiViT: Hierarchical Vision Transformer Meets Masked Image Modeling](https://arxiv.org/abs/2205.14949.pdf)|None
2022-06-01|LoMaR|Arxiv 2022|[Efficient Self-supervised Vision Pretraining with Local Masked Reconstruction](https://arxiv.org/pdf/2206.00790.pdf)|[LoMaR](https://github.com/junchen14/LoMaR)
2022-06-22|SemMAE|NeurIPS 2022|[SemMAE: Semantic-Guided Masking for Learning Masked Autoencoders](https://arxiv.org/pdf/2206.10207.pdf)|[SemMAE](https://github.com/ucasligang/SemMAE)
2022-08-11|MILAN|Arxiv 2022|[MILAN: Masked Image Pretraining on Language Assisted Representation](https://arxiv.org/pdf/2208.06049.pdf)|[MILAN](https://github.com/zejiangh/MILAN)
2022-11-14|EVA|Arxiv 2022|[EVA: Exploring the Limits of Masked Visual Representation Learning at Scale](https://arxiv.org/pdf/2211.07636.pdf)|[EVA](https://github.com/baaivision/EVA)
2022-11-28|AMT|Arxiv 2022|[Good helper is around you: Attention-driven Masked Image Modeling](https://arxiv.org/pdf/2211.15362.pdf)|[AMT](https://github.com/guijiejie/AMT)
2023-01-03|TinyMIM|CVPR 2023|[TinyMIM: An Empirical Study of Distilling MIM Pre-trained Models](https://arxiv.org/abs/2301.01296)|[TinyMIM](https://github.com/OliverRensu/TinyMIM)
2023-03-04|PixMIM|Arxiv 2023|[PixMIM: Rethinking Pixel Reconstruction in Masked Image Modeling](https://arxiv.org/pdf/2303.02416.pdf)|[PixMIM](https://github.com/open-mmlab/mmselfsup)
2023-03-09|LocalMIM|CVPR 2023|[Masked Image Modeling with Local Multi-Scale Reconstruction](https://arxiv.org/abs/2303.05251)|[LocalMIM](https://github.com/huawei-noah/Efficient-Computing/tree/master/Self-supervised/LocalMIM)
2023-03-12|AutoMAE|Arxiv 2023|[Improving Masked Autoencoders by Learning Where to Mask](https://arxiv.org/abs/2303.06583)|AutoMAE
2023-03-15|DeepMIM|Arxiv 2023|[DeepMIM: Deep Supervision for Masked Image Modeling](https://arxiv.org/abs/2303.08817)|[DeepMIM](https://github.com/OliverRensu/DeepMIM)
2023-04-25|Img2Vec|Arxiv 2023|[Img2Vec: A Teacher of High Token-Diversity Helps Masked AutoEncoders](https://arxiv.org/pdf/2304.12535.pdf)|None


# Others:
## Object detection.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2022-04-06|MIMDet|Arxiv 2022|[Unleashing Vanilla Vision Transformer with Masked Image Modeling for Object Detection](https://arxiv.org/pdf/2204.02964.pdf)|[MIMDet](https://github.com/hustvl/MIMDet)

## 3D.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2021-11-29|Point-BERT|CVPR 2022|[Point-BERT: Pre-training 3D Point Cloud Transformers with Masked Point Modeling](https://arxiv.org/pdf/2111.14819.pdf)|[Point-BERT](https://github.com/lulutang0608/Point-BERT)
2022-03-28|Point-MAE|ECCV 2022|[Masked Autoencoders for Point Cloud Self-supervised Learning](https://arxiv.org/pdf/2203.06604.pdf)|[Point-MAE](https://github.com/Pang-Yatian/Point-MAE)
2022-05-28|Point-M2AE|NeurIPS 2022|[Point-M2AE: Multi-scale Masked Autoencoders for Hierarchical Point Cloud Pre-training](https://arxiv.org/pdf/2205.14401.pdf)|[Point-M2AE](https://github.com/ZrrSkywalker/Point-M2AE)
2022-12-13|I2P-MAE|CVPR 2023|[Learning 3D Representations from 2D Pre-trained Models via Image-to-Point Masked Autoencoders](https://arxiv.org/pdf/2212.06785.pdf)|[I2P-MAE](https://github.com/ZrrSkywalker/I2P-MAE)


## Image generation.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2022-02-08|MaskGIT|Arxiv 2022|[MaskGIT: Masked Generative Image Transformer](https://arxiv.org/pdf/2202.04200.pdf)|None

## Unsupervised Domain Adaptation.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2023-06-18|MIC|CVPR 2023|[MIC: Masked Image Consistency for Context-Enhanced Domain Adaptation](https://arxiv.org/pdf/2212.01322.pdf)|None

## Video.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2021-12-02|BEVT|Arxiv 2021|[BEVT: BERT Pretraining of Video Transformers](https://arxiv.org/pdf/2112.01529.pdf)|[BEVT](https://github.com/xyzforever/BEVT)
2022-03-23|VideoMAE|NeurIPS 2022|[VideoMAE: Masked Autoencoders are Data-Efficient Learners for Self-Supervised Video Pre-Training](https://arxiv.org/abs/2203.12602)|[VideoMAE](https://github.com/MCG-NJU/VideoMAE)
2022-05-18|MAE_ST|NeurIPS 2022|[Masked Autoencoders As Spatiotemporal Learners](https://arxiv.org/pdf/2205.09113.pdf)|[MAE_ST](https://github.com/facebookresearch/mae_st)


## Multi-modal.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2022-04-04|MultiMAE|Arxiv 2022|[MultiMAE: Multi-modal Multi-task Masked Autoencoders](https://arxiv.org/pdf/2204.01678.pdf)|[MultiMAE](https://github.com/EPFL-VILAB/MultiMAE)
2022-05-27|M3AE|Arxiv 2022|[Multimodal Masked Autoencoders Learn Transferable Representations](https://arxiv.org/pdf/2205.14204.pdf)| None
2022-08-03|xxx|Arxiv 2022|[Masked Vision and Language Modeling for Multi-modal Representation Learning](https://arxiv.org/pdf/2208.02131.pdf)| None
2022-12-01|FLIP|Arxiv 2022|[Scaling Language-Image Pre-training via Masking](https://arxiv.org/pdf/2212.00794.pdf)| None

## Medical.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2022-03-10|MedMAE|Arxiv 2022|[Self Pre-training with Masked Autoencoders for Medical Image Analysis](https://arxiv.org/pdf/2203.05573.pdf)|None

## Analysis.
Date|Method|Conference|Title
-----|-----|-----|-----
2022-08-08|RelaxMIM|Arxiv 2022|[Understanding Masked Image Modeling via Learning Occlusion Invariant Feature](https://arxiv.org/pdf/2208.04164.pdf)

## Survey.
Date|Conference|Title
-----|-----|-----
2022-07-30|Arxiv 2022|[A Survey on Masked Autoencoder for Self-supervised Learning in Vision and Beyond](https://arxiv.org/pdf/2208.00173.pdf)
