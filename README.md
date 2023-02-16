## Key points
* Objectives: recognize the plant disease on plant leaf and fruit using RGB images
  * RGB image
  * leaf, fruit
  * plant: tomato, wheat
  * disease

## Datasets related with plant leaf disease
* Ag task: agricultural task
  * disease: disease classification or object detection
  * plant: plant identification
  * woody: woody identification
  * pest: pest detection or classification
* ML task: machine learning task, such as classification (cls), object detection (obj), segmentation (seg)
* Environment (env): where to take pictures, lab (lab), real scenario (real) such as field and greenhouse, from internet (internet) 
* Organs: leaf, fruit, flower, root, bark or stem, habitat

| Name         | env      | ML task  | Ag task | Plant             | img         | class | Paper                                                                                    | Dataset                                                                                                           |
|--------------|----------|----------|---------|-------------------|-------------|-------|------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| PlantVillage | lab      | cls      | disease | Multiple leaf     | 54,305      | 38    | [Paper](https://arxiv.org/abs/1511.08060)                                                | [Dataset](https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color)                                |
| PlantDoc     | internet | cls, obj | disease | Multiple leaf     | 2,598       | 27    | [Paper](https://dl.acm.org/doi/pdf/10.1145/3371158.3371196)                              | [Dataset](https://github.com/pratikkayal/PlantDoc-Dataset)                                                        |
| PDD271       | real     | cls      | disease | Multiple leaf     | 220,592     | 271   | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9325065&tag=1)              | [Sample](https://github.com/liuxindazz/PDD271)                                                                    |
| PDDB         | lab+real |          | disease | Multiple leaf     | 1,575       | 79    | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511018307797)             | [Dataset](https://www.digipathos-rep.cnptia.embrapa.br/jspui/)                                                    |
| PlantLeaf    | lab      | cls      | disease | Multiple leaf     | 4,503       | 12    | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9036158)                | [Dataset](https://data.mendeley.com/datasets/hb74ynkjcn/5)                                                        |
| TaiwanTomato | real+lab | cls      | disease | Tomato leaf       | 622         | 5     |                                                                                          | [Dataset](https://data.mendeley.com/datasets/ngdgg79rzb/1)                                                        |
| IVADL_tomato | real     | cls, obj | disease | Tomato leaf       | 17,063      | 9     |                                                                                          | [Dataset](https://github.com/IVADL/tomato-disease-detector)                                                       |
| IVADL_rose   | real     | cls, obj | disease | Rose leaf         | 23,114      | 6     |                                                                                          | [Dataset](https://github.com/IVADL/tomato-disease-detector)                                                       |
| Apple2020    | real     | cls      | disease | Apple leaf        | 3,642       | 4     | [Paper](https://bsapubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aps3.11390)        | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data)                                    |
| Apple2021    | real     | cls      | disease | Apple leaf        | 18,632      | 6     | [Paper](https://vision.cornell.edu/se3/wp-content/uploads/2021/09/029.pdf)               | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8/data)                                    |
| AppleObj     | lab+real | obj      | disease | Apple leaf        | 26,377      | 5     | [Paper](https://cdmd.cnki.com.cn/Article/CDMD-10712-1019901670.htm)                      |                                                                                                                   |
| Cassava      | real     | cls      | disease | Cassava leaf      | 21,397      | 5     | [Paper](https://www.frontiersin.org/articles/10.3389/fpls.2017.01852/full)               | [Dataset](https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data)                           |
| GoodCucumber | real     | cls      | disease | Cucumber leaf     | 691         | 2     |                                                                                          | [Dataset](https://www.kaggle.com/datasets/kareem3egm/cucumber-plant-diseases-dataset)                             |
| Citrus       | lab      | cls      | disease | Citrus fruit leaf | 105 + 609   | 5 + 5 | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919306948?via%3Dihub)  | [Dataset](https://data.mendeley.com/datasets/3f83gxmv57/2)                                                        |
| BRACOL       | lab      | cls, seg | disease | Coffee leaf       | 4,407       | 4     | [Paper](https://arxiv.org/abs/1907.11561)                                                | [Dataset](https://data.mendeley.com/datasets/yy2k5y8mxg/1)                                                        |
| RoCoLe       | real     | obj      | disease | Coffee leaf       | 1,560       | 2     | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919307693?via%3Dihub)  | [Dataset](https://data.mendeley.com/datasets/c5yvn32dzg/2)                                                        |
| JMuBEN       | real     | cls, seg | disease | Coffee leaf       | 58,555      | 5     | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921004261?via%3Dihub)  | [Dataset](https://www.sciencedirect.com/science/article/pii/S2352340921004261?via%3Dihub)                         |
| GoodCorn     | lab      | cls      | disease | Corn leaf         | 4,117       | 2     |                                                                                          | [Dataset](https://www.kaggle.com/datasets/rabbityashow/corn-leaf-diseasesnlb)                                     |
| Corn NLB     | real     | obj      | disease | Corn leaf         | 18,222      | 2     |                                                                                          | [Dataset](https://osf.io/p67rz/)                                                                                  |
| MerlotGrape  | real     | seg      | disease | Grape all         | 99          | 7     | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921005345?via%3Dihub)  | [Dataset](https://www.sciencedirect.com/science/article/pii/S2352340921005345?via%3Dihub)                         |
| DiaMOS       | real     | obj      | disease | Pear fruit        | 499 + 3,006 | 4     | [Paper](https://doi.org/10.5281/zenodo.5557313)                                          | [Dataset](https://doi.org/10.5281/zenodo.5557313)                                                                 |
| Rice5932     | real     | cls      | disease | Rice leaf         | 5,932       | 4     | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169919326997)             | [Dataset](https://data.mendeley.com/datasets/fwcj7stb8r/1)                                                        |
| Rice1426     | real     | cls      | disease | Rice leaf         | 1426        | 9     | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511020300830?via%3Dihub)  | [Dataset](https://drive.google.com/drive/folders/1ewBesJcguriVTX8sRJseCDbXAF_T4akK)                               |
| LWDCD2020    | real     | cls      | disease | Wheat spike       | 12,160      | 10    | [Paper](https://www.sciencedirect.com/science/article/pii/S2352914821001313)             | [Part ](https://github.com/lakshaygoyal425/Wheat-Disease-Detection)                                               |
| CGIAR        | real     | cls      | disease | wheat             | 876         | 3     |                                                                                          | [Dataset](https://www.kaggle.com/datasets/shadabhussain/cgiar-computer-vision-for-crop-disease?resource=download) |
| Corn2018     | real     | obj      | disease | corn              | 18,222      | 1     | [Paper](https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-018-3548-6)        | [Dataset](https://osf.io/p67rz/)                                                                                  |
| Corn2022     | real+lab | cls      | disease | corn              | 7,701       | 4     | [Paper](https://www.frontiersin.org/articles/10.3389/fpls.2022.864486/full)              | [Dataset](https://github.com/haiyang-qian/code-and-dataset)                                                       |
| Field-PV     | real     | cls      | disease | multiple          | 665         | 38    | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169921005408)             | [Dataset](https://github.com/PatrickGui/FPDR/tree/master)                                                         |
| Grape        |          |          |         | grape             |             | 4     |                                                                                          | [Dataset](https://www.kaggle.com/datasets/piyushmishra1999/plantvillage-grape)                                    |
| Black gram   | real+lab | cls      | disease | black gram        | 1,000       | 5     | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340922009295?via%3Dihub)  | [Dataset](https://data.mendeley.com/datasets/zfcv9fmrgv/3)                                                        |
|              |          |          |         |                   |             |       |                                                                                          |                                                                                                                   |
|              |          |          |         |                   |             |       |                                                                                          |                                                                                                                   |
|              |          |          |         |                   |             |       |                                                                                          |                                                                                                                   |

## Other types of plant
| Name          | env      | ML task  | Ag task      | Plant and organ      | img         | class  | Paper                                                                                           | Dataset                                                                                          |
|---------------|----------|----------|--------------|----------------------|-------------|--------|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| PlantCLEF2022 | real     | cls      | plant ident  | Multiple Multiple    | 2,885,052   | 80,000 | [Paper](https://www.aicrowd.com/challenges/lifeclef-2022-plant#citations)                       | [Dataset](https://www.imageclef.org/PlantCLEF2022)                                               | 
| Pl@ntNet-300K | real     | cls      | plant ident  | multiple             | 306,146     | 1,081  | [Paper](https://openreview.net/pdf?id=eLYinD0TtIt)                                              | [Dataset](https://zenodo.org/record/4726653#.YqSaOnZBwuV)                                        |
| MEW2014       | lab      | cls      | woody ident  | Multiple leaf        |             | 151    | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511013000731)                    | [Dataset](http://zoi.utia.cas.cz/node/662)                                                       | 
| IP102         | real     | cls, obj | pest         |                      | 75,000      | 102    | [Paper](https://ieeexplore.ieee.org/document/8954351)                                           | [Dataset](https://github.com/xpwu95/IP102)                                                       |
| TomatoPest8   | real     | cls      | pest         | tomato pest          | 609         | 8      |                                                                                                 | [Dataset](https://data.mendeley.com/datasets/s62zm6djd2/1)                                       |
| Soybean       | real     | cls      | pest leaf    | soybean leaf         | 6,410       | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921010313?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/bycbh73438/1)                                       |
| GWHD          | real     | obj      | wheat head   | wheat head           |             |        | [Paper](https://arxiv.org/abs/2005.02162)                                                       | [Dataet](https://www.kaggle.com/competitions/global-wheat-detection/data)                        |
| F.margarita   | real     | obj      | growth stage | Fortunella margarita | 1,031       | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921005771?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/wnv4bszczz/1)                                       |
| PomegraGrade  | lab      | cls      | fruit grade  | Pomegranate Fruit    |             | 3      | [paper](https://doi.org/10.1016/j.dib.2021.107249)                                              | [Dataset](https://www.kaggle.com/datasets/kumararun37/pomegranate-fruit-dataset)                 |
| Medjool       | lab      | cls, obj | fruit grade  | dates                | 2,576       | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921004005?via%3Dihub)         | [Dataset](http://dx.doi.org/10.17632/872xk9npmz.1)                                               |
| FruitNet      | real     | cls      | fruit grade  | Multiple fruit       | 19,526      | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921009616?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/b6fftwbr2v/1)                                       |
| SoybeanSeed   | lab      | cls      | seed grade   | soybean seed         |             |        | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919300010?via%3Dihub)         |                                                                                                  |
| ChineseHerb   | real     | cls, seg | flower cls   | Multiple flower      | 1,716       | 12     | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921009306?via%3Dihub#fig0001) | [Dataset](https://doi.org/10.17632/r3z6vp396m.1)                                                 |
| Flower103     | real     | cls, seg | flower cls   | Multiple flower      |             | 103    | [Paper](https://ieeexplore.ieee.org/document/4756141)                                           |                                                                                                  |
| WeedRobot     | real     | obj      | weed         | Multiple Multiple    | 1,118       |        | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340920307277?via%3Dihub )        | [Dataset](https://data.mendeley.com/datasets/nj4vtk4tt6/1)                                       |

 
## Backup
* [Chinese crop disease dataset, images with water mark](https://www.scidb.cn/en/detail?dataSetId=633694461276192770)
* [Chinese grape disease, with water mark](https://www.scidb.cn/en/detail?dataSetId=76b39c9c435d4035b5076412c2ddcb61)
* 
* [plantnet website](https://plantnet.org/en/)
* [python library for food, agriculture](https://github.com/Project-AgML/AgML)
* [China agricultural disease and pest dataset but not available](http://www.icgroupcas.cn/website_bchtk/tuku_jiangdou.html)
* [Grape disease](https://link.springer.com/chapter/10.1007/978-3-031-06430-2_32)
* [PlantifyDr software](https://www.kaggle.com/datasets/lavaman151/plantifydr-dataset)
* [Ariel image](https://arxiv.org/pdf/2004.09754.pdf)
* [ICL plant woody identification](https://ieeexplore.ieee.org/document/6257486)
* [Vegetable crops at an early stage](https://www.sciencedirect.com/science/article/pii/S2352340922002463?via%3Dihub)
* [Fuji apple 3D point cloud](https://doi.org/10.1016/j.dib.2021.107629)
* [Soybean seed grade, not image](https://www.sciencedirect.com/science/article/pii/S2352340919300010?via%3Dihub)
* [whitefly counting](https://doi.org/10.1016/j.dib.2022.107911)
* [Cassava root](https://doi.org/10.1016/j.dib.2020.106170)
* [pineapple and others dataset](https://github.com/rodrigobressan/digipathos)
* [Plant detection application](https://github.com/PuneethReddyHC/leaf-diseases-predition)

* [Wheat powdery mildew dataset](https://www.scidb.cn/en/detail?dataSetId=557575344966598656)
* [Remote sense different types of crop for harvest](https://openreview.net/forum?id=JtjzUXPEaCu)
* [UAV for plant disease](https://osf.io/p67rz/)

## Korea plant related dataset
https://aihub.or.kr/aidata/30732

https://aihub.or.kr/aidata/30731

https://aihub.or.kr/aidata/30730

https://aihub.or.kr/aidata/30726

https://aihub.or.kr/aidata/27768

https://aihub.or.kr/aidata/30727

https://aihub.or.kr/aidata/30729

https://aihub.or.kr/aidata/30728

https://aihub.or.kr/aidata/34149

https://aihub.or.kr/aidata/129



## Contribute this project
Please fell free to contribute this project.


## To cite this project
If this project is useful for you, please cite this project.
```
@misc{MinglePlant,
  author={Mingle Xu},
  title={Plant Disease Recognition Datasets},
  howpublished={\url{https://github.com/xml94/Plant_disease_recognition}},
}
```
