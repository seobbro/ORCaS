# ORCaS
Official repo for ORCaS: Unsupervised Depth Completion via Occluded Region Completion as Supervision, ICLR 2026.
# ORCaS: Unsupervised Depth Completion via Occluded Region Completion as Supervision

[cite_start][![Paper](https://img.shields.io/badge/Paper-ICLR_2026-blue.svg)](#) This is the official repository for the ICLR 2026 paper **ORCaS: Unsupervised Depth Completion via Occluded Region Completion as Supervision**[cite: 1, 2]. 

[cite_start]**Authors:** Hyoungseob Park¹, Runjian Chen², Patrick Rim¹, Dong Lao³, Alex Wong¹ [cite: 3]  
[cite_start]**Affiliations:** ¹Yale University, ²University of Hong Kong, ³Louisiana State University [cite: 3]

---

## 📢 Announcement
[cite_start]**The code and the pretrained weights for ORCaS will be released soon.** [cite: 340] 

Please star or watch this repository to be notified of the release!

## 📖 Abstract
[cite_start]We propose a method for inferring an egocentric dense depth map from an RGB image and a sparse point cloud[cite: 5]. [cite_start]The crux of our method lies in modeling the 3D scene implicitly within the latent space and learning an inductive bias in an unsupervised manner through principles of Structure-from-Motion[cite: 6]. 

[cite_start]To force the learning of this inductive bias, we propose to optimize for an ill-posed objective during training: predicting latent features that are not observed in the input view, but exist in the 3D scene[cite: 7]. [cite_start]"Empty" regions in the latent space that correspond to regions occluded from the input view are completed by a Contextual eXtrapolation (ConteXt) mechanism based on features visible in input view[cite: 9]. [cite_start]We term our method "Occluded Region Completion as Supervision" or ORCaS[cite: 11].

## 🏆 Key Results
* [cite_start]**State-of-the-Art Performance:** We evaluate ORCaS on VOID1500 and NYUv2 benchmark datasets, where we improve over the best existing method by 8.91% across all metrics[cite: 12].
* [cite_start]**Generalization:** ORCaS improves generalization from VOID1500 to ScanNet and NYUv2 by 15.7%[cite: 13].
* [cite_start]**Robustness:** Improves robustness to low density inputs by 31.2%[cite: 13].

## 📝 Citation
If you find our work useful in your research, please consider citing:

```bibtex
@inproceedings{park2026orcas,
  title={ORCaS: Unsupervised Depth Completion via Occluded Region Completion as Supervision},
  author={Park, Hyoungseob and Chen, Runjian and Rim, Patrick and Lao, Dong and Wong, Alex},
  booktitle={The Fourteenth International Conference on Learning Representations},
  year={2026}
}
