## Key points
* Objectives: recognize the plant disease on plant leaf and fruit using RGB images
* Foliar disease
* Tasks: image classification (cls), object detection (obj), segmentation (seg) 

## Datasets
* Ag task: agricultural task
  * disease cls: disease classification
  * plant ide: plant identification
* ML task: machine learning task, such as classification (cls), object detection (obj), segmentation (seg)
* Environment: where to take pictures, lab (lab), real scenario (real) such as field and greenhouse, from internet (internet) 
* Organs: leaf, fruit, flower, root, bark or stem, habitat

| Name          | Environment | Ag task        | Plant and organ    | img         | class  | ML task  | Paper                                                                                   | Dataset                                                                                          |
|---------------|-------------|----------------|--------------------|-------------|--------|----------|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Pathology2020 | real        | disease cls    | Apple leaf         | 3,642       | 3      | cls      | [Paper](https://bsapubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aps3.11390)       | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data)                   |
| Pathology2021 | real        | disease cls    | Apple leaf         |             |        | cls      |                                                                                         | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8/leaderboard?tab=public) |
| Cassava       | real        | disease cls    | Cassava leaf       | 21,397      | 5      | cls      | [Paper](https://www.frontiersin.org/articles/10.3389/fpls.2017.01852/full)              | [Dataset](https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data)          |
| PlantVillage  | lab         | disease cls    | Multiple leaf      | 54,305      | 38     | cls      | [Paper](https://arxiv.org/abs/1511.08060)                                               | [Dataset](https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color)               |
| GoodCucumber  | real        | disease cls    | Cucumber leaf      | 691         | 2      | cls      |                                                                                         | [Dataset](https://www.kaggle.com/datasets/kareem3egm/cucumber-plant-diseases-dataset)            |
| PlantDoc      | internet    | disease cls    | Multiple leaf (13) | 2,598       | 17     | cls, obj | [Paper](https://dl.acm.org/doi/pdf/10.1145/3371158.3371196)                             | [Dataset](https://github.com/pratikkayal/PlantDoc-Dataset)                                       |
| Citrus        | lab         | disease cls    | Citrus fruit leaf  | 105 + 609   | 5 + 5  | cls      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919306948?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/3f83gxmv57/2)                                       |
| DiaMOS        | real        | disease cls    | Pear fruit leaf    | 499 + 3,006 | 4      | obj      | [Paper](https://doi.org/10.5281/zenodo.5557313)                                         | [Dataset](https://doi.org/10.5281/zenodo.5557313)                                                |
| BRACOL        | lab         | disease cls    | Coffee leaf        | 4,407       | 4      | obj, seg | [Paper](https://arxiv.org/abs/1907.11561)                                               | [Dataset](https://data.mendeley.com/datasets/yy2k5y8mxg/1)                                       |
| RoCoLe        | real        | disease cls    | Coffee leaf        | 1,560       | 2      | obj      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919307693?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/c5yvn32dzg/2)                                       |
| PDD271        | real        | disease cls    | Multiple           | 220,592     | 271    | cls      | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9325065&tag=1)             |                                                                                                  |
| RiceLeaf2020  | real        | disease cls    | Rice leaf          | 5,932       | 4      | cls      | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169919326997)            | [Dataset](https://data.mendeley.com/datasets/fwcj7stb8r/1)                                       |
| AppleObj      | lab + real  | disease cls    | Apple leaf         | 26,377      | 5      | obj      | [Paper](https://cdmd.cnki.com.cn/Article/CDMD-10712-1019901670.htm)                     | [Dataset](https://aistudio.baidu.com/aistudio/datasetdetail/11591)                               |
| GoodCorn      | lab         | disease cls    | Corn leaf          | 4,117       | 2      | cls      |                                                                                         | [Dataset](https://www.kaggle.com/datasets/rabbityashow/corn-leaf-diseasesnlb)                    |
| PDDB          | lab + real  | disease cls    | Multiple           | 50,000      | 171    |          | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511018307797)            | [Dataset](https://www.digipathos-rep.cnptia.embrapa.br/jspui/)                                   |
| PlantCLEF2022 | real        | plant ide      | Multiple Multiple  | 2,885,052   | 80,000 | cls      | [Paper](https://www.aicrowd.com/challenges/lifeclef-2022-plant#citations)               | [Dataset](https://www.imageclef.org/PlantCLEF2022)                                               | 
| MEW2014       | lab         | woody ide      | Multiple leaf      |             | 151    | cls      | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511013000731)            | [Dataset](http://zoi.utia.cas.cz/node/662)                                                       | 
| IP102         |             | pest cls       |                    | 75,000      | 102    | cls, obj | [Paper](https://ieeexplore.ieee.org/document/8954351)                                   | [Dataset](https://github.com/xpwu95/IP102)                                                       |
| GWHD          | real        | head detection | wheat head         |             |        |          | [Paper](https://arxiv.org/abs/2005.02162)                                               | [Dataet](https://www.kaggle.com/competitions/global-wheat-detection/data)                        |
| LWDCD2020     | real        | disease        | wheat spike leaf   | 12,160      | 10     | cls      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352914821001313)            | [Dataset](https://github.com/lakshaygoyal425/Wheat-Disease-Detection)                            |
| example       |             |                |                    |             |        |          |                                                                                         |                                                                                                  |

 
## Backup
* [python library for food, agriculture](https://github.com/Project-AgML/AgML)
* [China agricultural disease and pest dataset but not available](http://www.icgroupcas.cn/website_bchtk/tuku_jiangdou.html)
* [Grape disease](https://link.springer.com/chapter/10.1007/978-3-031-06430-2_32)
* [PlantifyDr software](https://www.kaggle.com/datasets/lavaman151/plantifydr-dataset)
* [Ariel image](ttps://arxiv.org/pdf/2004.09754.pdf)
* [ICL plant woody identification](https://ieeexplore.ieee.org/document/6257486)


## To cite this
If this project is useful for you, please cite this project.
```
@misc{MinglePlant,
  author={Mingle Xu},
  title={Plant Disease Recognition Datasets},
  howpublished={\url{https://github.com/xml94/Plant_disease_recognition}},
}
```
