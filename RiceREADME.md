# Rice Leaf Disease Dataset
Only count the images with public labels.

type of disease:
* BLB, Bacterial Light Black
* BLS, Bacterial Leaf Streak
* BPB, Bacterial Panicle Blight
* BSB, Black Stem Borer
* Blast
* BS: Brown Spot
* DH: Dead Heart
* DM: Downy Mildew
* FS: False Smut. same to dead heart?
* Hispa
* LR: Leaf Roller
* LS: Leaf Smut
* NB: Neck Blast
* SBR: Sheath Blight Rot
* Stemborer
* Tungro
* WSB: White Stem Borer
* YSB: Yellow Stem Borer
* Healthy

| Name               | env  | ML task   | img    | class                                                        | Paper and some info                                                                               | Download Link                                                                                   |
|--------------------|------|-----------|--------|--------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| PaddyDoctor10407   | real | cls       | 10,407 | 10: Blast, BLB, BLS, BPB, BS, DH, DM, Healthy, Hispa, Tungro | [arXiv](https://arxiv.org/abs/2205.11108)                                                         | [link](https://www.kaggle.com/competitions/paddy-disease-classification/overview)               |
| Rice5932           | real | cls       | 5,932  | 4: Blast, BLB, BS, Tungro                                    | [journal](https://www.sciencedirect.com/science/article/pii/S0168169919326997)                    | [link](https://data.mendeley.com/datasets/fwcj7stb8r/1)                                         |
| Rice1426           | real | cls       | 1,426  | 9: BLB, BPH, BS, FS, Healthy, Hispa, NB, SBR, Stemborer      | [journal](https://www.sciencedirect.com/science/article/pii/S1537511020300830?via%3Dihub)         | [link](https://drive.google.com/drive/folders/1ewBesJcguriVTX8sRJseCDbXAF_T4akK)                |
| PhilippinesRice552 | real | cls & obj | 226    | 3: BLB, Blast, BS                                            | Bounding boxes are not precise.                                                                   | [link](https://github.com/aldrin233/RiceDiseases-DataSet)                                       |
| ChinaRiceFS86      | real | cls       | 86     | 1: FS                                                        | [journal](https://www.sciencedirect.com/science/article/pii/S1537511022000770?via%3Dihub#appsec1) | [Link](https://www.sciencedirect.com/science/article/pii/S1537511022000770?via%3Dihub#appsec1)  |
| NigeriaRice3355    | lab  | cls       | 3,355  | 4: Blast, BS, Healthy, Hispa                                 | Big resolution                                                                                    | [link](https://www.kaggle.com/datasets/minhhuy2810/rice-diseases-image-dataset)                 |
| IndonesiaRice240   | lab  | cls       | 240    | 3: Blast, Blight, Tungro                                     |                                                                                                   | [link](https://www.kaggle.com/datasets/tedisetiady/leaf-rice-disease-indonesia)                 |
| UCIRice120         | lab  | cls       | 120    | 3: BLB, BS, LS                                               |                                                                                                   | [link](https://archive.ics.uci.edu/ml/datasets/rice+leaf+diseases)                              |
|                    |      |           |        |                                                              |                                                                                                   |                                                                                                 |

Some datasets are generated from NigeriaRice3355, such as [smaller resolution](https://www.kaggle.com/datasets/nizorogbezuode/rice-leaf-images) and [balanced](https://www.kaggle.com/datasets/jonathanrjpereira/rice-disease).

