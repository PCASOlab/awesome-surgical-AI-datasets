# awesome-surgical-AI-datasets

## Video/Image

| Dataset | Modality | Robo/Lap/Micro/Endo/Open | Procedure | Instrument (p/b/f) | Instrument ID | Target (p/b/f) | Verb (s/b/p) | Triplet | Phase | N cases | Link |
|:--------|:--------:|:------------------------:|:---------:|:------------------:|:-------------:|:--------------:|:------------:|:-------:|:-----:|:-------:|:-----|
| Cholec80 | Video | Lap | Cholecystectomy | Frame | Y | N | N | N | Y | 80 | [project](https://camma.u-strasbg.fr/datasets/cholec80/) |
| CholecT50 | Video | Lap | Cholecystectomy | Frame | Y | Frame | Frame | Y | N | 50 | [GitHub](https://github.com/CAMMA-public/cholect50) |
| CholecT45 | Video | Lap | Cholecystectomy | Frame | Y | Frame | Frame | Y | N | 45 | [GitHub](https://github.com/CAMMA-public/cholect45) |
| CholecT40 | Video | Lap | Cholecystectomy | Frame | Y | Frame | Frame | Y | N | 40 | [GitHub](https://github.com/CAMMA-public/cholect40) |
| CholecTrack20 | Video | Lap | Cholecystectomy | Box | Y | N | N | N | Y | 20 | [project](https://camma.u-strasbg.fr/datasets/cholectrack20/) |
| CholecSeg8k | Video | Lap | Cholecystectomy | Pixel | Y | Pixel | N | N | N | 17 | [GitHub](https://github.com/CAMMA-public/CholecSeg8k) |
| Cholec80+HTA | Video | Lap | Cholecystectomy | N | N | N | N | N | Y | 80 | [link](https://github.com/bnamazi/HTA_3D_CNN/tree/master/data/All_chole80_annotations) |
| HeiCo | Video | Lap | Colorectal | Pixel | N | N | N | N | Y | 30 | [Synapse](https://www.synapse.org/#!Synapse:syn21903917/wiki/601992) |
| MultiBypass140 | Video | Lap | LRYGB | N | N | N | N | N | Y | 140 | [GitHub](https://github.com/CAMMA-public/MultiBypass140) |
| Endoscapes-CVS201 | Video | Lap | Cholecystectomy | N | N | N | N | N | N | 201 | [GitHub](https://github.com/CAMMA-public/Endoscapes) |
| Endoscapes-BBox201 | Video | Lap | Cholecystectomy | Box | Y | Box | N | N | N | 201 | [GitHub](https://github.com/CAMMA-public/Endoscapes) |
| Endoscapes-Seg50 | Video | Lap | Cholecystectomy | Pixel | Y | Pixel | N | N | N | 50 | [GitHub](https://github.com/CAMMA-public/Endoscapes) |
| Cataract-1K | Video | Micro | Cataract | Pixel | Y | Pixel | N | N | Y | 1000 | [GitHub](https://github.com/Negin-Ghamsarian/Cataract-1K) |

## 3D/4D

| Dataset | Modality | Camera motion | Procedure | Scene | Instrument (p/b/f) | Instrument ID | Human (p/b/f) | Verb | Triplet | Phase | Scene graph | N cases | Link |
|:--------|:--------:|:-------------:|:---------:|:-----:|:------------------:|:-------------:|:-------------:|:----:|:-------:|:-----:|:-----------:|:-------:|:-----|
| 4D-OR | RGB-D Video | - | - | Room | Box (3D) | - | Box (6D) | Role | N | Y | Y | 6734 | [GitHub](https://github.com/egeozsoy/4D-OR) |
| StereoMIS | Stereo Video | Forward Kinematics | Animal | Lap | - | - | - | - | - | - | - | 11 | [Zenodo](https://zenodo.org/records/7727692) |

## Additional notable surgical datasets

| Dataset | Modality | Procedure | Link |
|:--------|:--------:|:---------:|:-----|
| CATARACTS | Video | Cataract | [challenge](http://cataracts.grand-challenge.org/) |
| M2CAI16 Workflow Challenge | Video | Cholecystectomy | [Synapse](https://www.synapse.org/#!Synapse:syn31937149) |
| MICCAI EndoVis 2017 | Video | Robotic surgery | [challenge](https://endovis.grand-challenge.org/EndoVis2017/) |
| MICCAI EndoVis 2018 | Video | Robotic surgery | [challenge](https://endovis.grand-challenge.org/EndoVis2018/) |
| MICCAI EndoVis 2019 | Video | Robotic surgery | [challenge](https://endovis.grand-challenge.org/EndoVis2019/) |
| SCARED | RGB-D Video | Endoscopic scene understanding | [challenge](https://endovissub2019-scared.grand-challenge.org/) |
| SurgAtlas | Video | 15,291 videos / 2,391 hours / 18 specialties / 5,000+ procedures; raw open and MIS recordings | — |
| SurgVU | Video + system data | Da Vinci console-view training exercises on porcine tissue; synchronized video and system telemetry | — |
| AVOS | Video | 1,997 open-surgery videos across 50 countries and 23 procedure types; tool/hand and keypoint annotations | — |
| SLAM | Video | 4,097 clips across 34 patient directories; laparoscopic cholecystectomy and appendectomy with 7 action labels | — |
| Surg-3M | Video | 4,000+ surgical videos totaling 938 hours; curated, high-quality surgical footage | — |
| TEMSET-24K | Video | De-identified multi-part endoscopic recordings and microclips for timeline segmentation and video analytics | — |