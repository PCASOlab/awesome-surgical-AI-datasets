# awesome-surgical-AI-datasets
## Video/Image

| Dataset | Modality | Robo/Lap/ Micro/Endo/Open | Procedure | Instrument (p/b/f) | Instrument ID | Target (p/b/f) | Verb (s/b/p) | Triplet | Phase | N cases | Link |
|:--------|:-----:|:---:|:---------------:|:--------:|:-:|:--------:|:--------:|:-:|:--:|:--:|:-----|  
| Cholec80      | Video | Lap | Cholecystectomy | Frame | Y | N        | N        | N | Y | 80 | link |
| CholecT50     | Video | Lap | Cholecystectomy | Frame | Y | Frame | Frame | Y | N | 50 | link |
| CholecT45     | Video | Lap | Cholecystectomy | Frame | Y | Frame | Frame | Y | N | 45 | link |
| CholecT40     | Video | Lap | Cholecystectomy | Frame | Y | Frame | Frame | Y | N | 40 | link |
| CholecTrack20 | Video | Lap | Cholecystectomy | Box   | Y | N     | N     | N | Y | 20 | link |
| CholecSeg8k   | Video | Lap | Cholecystectomy | Pixel | Y | Pixel | N     | N | N | 17 | link |
| Cholec80+HTA  | Video | Lap | Cholecystectomy | N     | N | N     | N     | N | Y | 80 | [link](https://github.com/bnamazi/HTA_3D_CNN/tree/master/data/All_chole80_annotations) |
| HeiCo         | Video | Lap | Colorectal      | Pixel | N | N     | N     | N | Y | 30 | [link](https://www.synapse.org/#!Synapse:syn21903917/wiki/601992) |
| MultiBypass140 | Video | Lap | LRYGB      | N | N | N     | N     | N | Y | 140 | [link]([https://www.synapse.org/#!Synapse:syn21903917/wiki/601992](https://github.com/CAMMA-public/MultiBypass140)https://github.com/CAMMA-public/MultiBypass140) |
| Endoscapes-CVS201 | Video | Lap | Cholecystectomy | N | N | N | N | N | N | 201 | [link](https://github.com/CAMMA-public/Endoscapes) |
| Endoscapes-BBox201 | Video | Lap | Cholecystectomy | Box | Y | Box | N | N | N | 201 | [link](https://github.com/CAMMA-public/Endoscapes) |
| Endoscapes-Seg50 | Video | Lap | Cholecystectomy | Pixel | Y | Pixel | N | N | N | 50 | [link](https://github.com/CAMMA-public/Endoscapes) |
| Cataract-1K      | Video | Micro | Cataract      | Pixel | Y | Pixel | N | N | Y | 1000 | [link](https://github.com/Negin-Ghamsarian/Cataract-1K) |



## 3D/4D

| Dataset | Modality      | Camera motion | Procedure | Scene | Instrument (p/b/f) | Instrument ID | Human (p/b/f) | Verb     | Triplet | Phase | Scene graph | N cases | Link |
|:--------|:-------------:|:-------------:|:---------:|:-----:|:------------------:|:-------------:|:-------------:|:--------:|:-------:|:-----:|:-----------:|:-------:|:----:| 
| 4D-OR   | RGB-D Video   |  -            |  -        | Room  |   Box (3D)         |               | Box (6D)      | Role     | N       | Y     | Y           |6734     | [link](https://github.com/egeozsoy/4D-OR) |
| StereoMIS| Stereo Video | Forward Kinematics | Animal | Lap |                    |               |               |          |         |       |             | 11      |  [link](https://zenodo.org/records/7727692)|
