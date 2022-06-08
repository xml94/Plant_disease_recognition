## Key points
* Objectives: recognize the plant disease on plant leaf and fruit using RGB images
  * RGB image
  * leaf, fruit
  * plant: tomato, wheat
  * disease

## Datasets
* Ag task: agricultural task
  * disease: disease classification or object detection
  * plant: plant identification
  * woody: woody identification
  * pest: pest detection or classification
* ML task: machine learning task, such as classification (cls), object detection (obj), segmentation (seg)
* Environment (env): where to take pictures, lab (lab), real scenario (real) such as field and greenhouse, from internet (internet) 
* Organs: leaf, fruit, flower, root, bark or stem, habitat

| Name          | env      | ML task  | Ag task      | Plant and organ      | img         | class  | Paper                                                                                           | Dataset                                                                                          |
|---------------|----------|----------|--------------|----------------------|-------------|--------|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Pathology2020 | real     | cls      | disease      | Apple leaf           | 3,642       | 3      | [Paper](https://bsapubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aps3.11390)               | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data)                   |
| Pathology2021 | real     | cls      | disease      | Apple leaf           | 18,632      |        |                                                                                                 | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8/leaderboard?tab=public) |
| Cassava       | real     | cls      | disease      | Cassava leaf         | 21,397      | 5      | [Paper](https://www.frontiersin.org/articles/10.3389/fpls.2017.01852/full)                      | [Dataset](https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data)          |
| PlantVillage  | lab      | cls      | disease      | Multiple leaf        | 54,305      | 38     | [Paper](https://arxiv.org/abs/1511.08060)                                                       | [Dataset](https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color)               |
| GoodCucumber  | real     | cls      | disease      | Cucumber leaf        | 691         | 2      |                                                                                                 | [Dataset](https://www.kaggle.com/datasets/kareem3egm/cucumber-plant-diseases-dataset)            |
| PlantDoc      | internet | cls, obj | disease      | Multiple leaf (13)   | 2,598       | 17     | [Paper](https://dl.acm.org/doi/pdf/10.1145/3371158.3371196)                                     | [Dataset](https://github.com/pratikkayal/PlantDoc-Dataset)                                       |
| Citrus        | lab      | cls      | disease      | Citrus fruit leaf    | 105 + 609   | 5 + 5  | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919306948?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/3f83gxmv57/2)                                       |
| DiaMOS        | real     | obj      | disease      | Pear fruit leaf      | 499 + 3,006 | 4      | [Paper](https://doi.org/10.5281/zenodo.5557313)                                                 | [Dataset](https://doi.org/10.5281/zenodo.5557313)                                                |
| BRACOL        | lab      | obj, seg | disease      | Coffee leaf          | 4,407       | 4      | [Paper](https://arxiv.org/abs/1907.11561)                                                       | [Dataset](https://data.mendeley.com/datasets/yy2k5y8mxg/1)                                       |
| RoCoLe        | real     | obj      | disease      | Coffee leaf          | 1,560       | 2      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919307693?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/c5yvn32dzg/2)                                       |
| PDD271        | real     | cls      | disease      | Multiple             | 220,592     | 271    | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9325065&tag=1)                     |                                                                                                  |
| RiceLeaf2020  | real     | cls      | disease      | Rice leaf            | 5,932       | 4      | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169919326997)                    | [Dataset](https://data.mendeley.com/datasets/fwcj7stb8r/1)                                       |
| AppleObj      | lab+real | obj      | disease      | Apple leaf           | 26,377      | 5      | [Paper](https://cdmd.cnki.com.cn/Article/CDMD-10712-1019901670.htm)                             | [Dataset](https://aistudio.baidu.com/aistudio/datasetdetail/11591)                               |
| GoodCorn      | lab      | cls      | disease      | Corn leaf            | 4,117       | 2      |                                                                                                 | [Dataset](https://www.kaggle.com/datasets/rabbityashow/corn-leaf-diseasesnlb)                    |
| PDDB          | lab+real |          | disease      | Multiple             | 50,000      | 171    | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511018307797)                    | [Dataset](https://www.digipathos-rep.cnptia.embrapa.br/jspui/)                                   |
| PlantCLEF2022 | real     | cls      | plant        | Multiple Multiple    | 2,885,052   | 80,000 | [Paper](https://www.aicrowd.com/challenges/lifeclef-2022-plant#citations)                       | [Dataset](https://www.imageclef.org/PlantCLEF2022)                                               | 
| MEW2014       | lab      | cls      | woody        | Multiple leaf        |             | 151    | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511013000731)                    | [Dataset](http://zoi.utia.cas.cz/node/662)                                                       | 
| IP102         | real     | cls, obj | pest         |                      | 75,000      | 102    | [Paper](https://ieeexplore.ieee.org/document/8954351)                                           | [Dataset](https://github.com/xpwu95/IP102)                                                       |
| GWHD          | real     | obj      | wheat head   | wheat head           |             |        | [Paper](https://arxiv.org/abs/2005.02162)                                                       | [Dataet](https://www.kaggle.com/competitions/global-wheat-detection/data)                        |
| LWDCD2020     | real     | cls      | disease      | wheat spike leaf     | 12,160      | 10     | [Paper](https://www.sciencedirect.com/science/article/pii/S2352914821001313)                    | [Dataset](https://github.com/lakshaygoyal425/Wheat-Disease-Detection)                            |
| Corn NLB      | real     | obj      | disease      | corn leaf            | 18,222      | 2      |                                                                                                 | [Dataset](https://osf.io/p67rz/)                                                                 |
| TomatoPest8   | real     | cls      | pest         | tomato               | 609         | 8      |                                                                                                 | [Dataset](https://data.mendeley.com/datasets/s62zm6djd2/1)                                       |
| Soybean       | real     | cls      | pest leaf    | soybean leaf         | 6,410       | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921010313?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/bycbh73438/1)                                       |
| F.margarita   | real     | obj      | growth stage | Fortunella margarita | 1,031       | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921005771?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/wnv4bszczz/1)                                       |
| PomegraGrade  | lab      | cls      | fruit grade  | Pomegranate Fruit    |             | 3      | [paper](https://doi.org/10.1016/j.dib.2021.107249)                                              | [Dataset](https://www.kaggle.com/datasets/kumararun37/pomegranate-fruit-dataset)                 |
| WeedRobot     | real     | obj      | weed         | Multiple Multiple    | 1,118       |        | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340920307277?via%3Dihub )        | [Dataset](https://data.mendeley.com/datasets/nj4vtk4tt6/1)                                       |
| FruitNet      | real     | cls      | fruit grade  | Multiple fruit       | 19,526      | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921009616?via%3Dihub)         | [Dataset](https://data.mendeley.com/datasets/b6fftwbr2v/1)                                       |
| SoybeanSeed   | lab      | cls      | seed grade   | soybean seed         |             |        | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919300010?via%3Dihub)         |                                                                                                  |
| MerlotGrape   | real     | seg      | disease seg  | grape all            | 99          | 7      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921005345?via%3Dihub)         | [Dataset](https://www.sciencedirect.com/science/article/pii/S2352340921005345?via%3Dihub)        |
| ChineseHerb   | real     | cls, seg | flower cls   | Multiple flower      | 1,716       | 12     | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921009306?via%3Dihub#fig0001) | [Dataset](https://doi.org/10.17632/r3z6vp396m.1)                                                 |
| Flower103     | real     | cls, seg | flower cls   | Multiple flower      |             | 103    | [Paper](https://ieeexplore.ieee.org/document/4756141)                                           |                                                                                                  |
| JMuBEN        | real     | cls, seg | disease      | Coffee leaf          | 58,555      | 5      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921004261?via%3Dihub)         | [Dataset](https://www.sciencedirect.com/science/article/pii/S2352340921004261?via%3Dihub)        |
| Medjool       | lab      | cls, obj | fruit grade  | dates                | 2,576       | 3      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340921004005?via%3Dihub)         | [Dataset](http://dx.doi.org/10.17632/872xk9npmz.1)                                               |
| PlantLeaf     | lab      | cls      | multiple     | Multiple             | 4,503       | 22     |                                                                                                 | [Dataset](https://data.mendeley.com/datasets/hb74ynkjcn/5)                                       |
| example       |          |          |              |                      |             |        |                                                                                                 |                                                                                                  |

 
## Backup
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


## Contribute this project
Please fell free to contribute this project.
You can follow the example in the table.

## To cite this project
If this project is useful for you, please cite this project.
```
@misc{MinglePlant,
  author={Mingle Xu},
  title={Plant Disease Recognition Datasets},
  howpublished={\url{https://github.com/xml94/Plant_disease_recognition}},
}
```
