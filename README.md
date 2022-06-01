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
* Environment: where to take pictures, lab (lab), real scenario (real) such as field and greenhouse, from internet (internet) 
* Organs: leaf, fruit, flower, root, bark or stem, habitat

| Name          | Environment | ML task  | Ag task    | Plant and organ    | img         | class    | Paper                                                                                   | Dataset                                                                                          |
|---------------|-------------|----------|------------|--------------------|-------------|----------|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Pathology2020 | real        | cls      | disease    | Apple leaf         | 3,642       | 3        | [Paper](https://bsapubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aps3.11390)       | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data)                   |
| Pathology2021 | real        | cls      | disease    | Apple leaf         |             |          |                                                                                         | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8/leaderboard?tab=public) |
| Cassava       | real        | cls      | disease    | Cassava leaf       | 21,397      | 5        | [Paper](https://www.frontiersin.org/articles/10.3389/fpls.2017.01852/full)              | [Dataset](https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data)          |
| PlantVillage  | lab         | cls      | disease    | Multiple leaf      | 54,305      | 38       | [Paper](https://arxiv.org/abs/1511.08060)                                               | [Dataset](https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color)               |
| GoodCucumber  | real        | cls      | disease    | Cucumber leaf      | 691         | 2        |                                                                                         | [Dataset](https://www.kaggle.com/datasets/kareem3egm/cucumber-plant-diseases-dataset)            |
| PlantDoc      | internet    | cls, obj | disease    | Multiple leaf (13) | 2,598       | 17       | [Paper](https://dl.acm.org/doi/pdf/10.1145/3371158.3371196)                             | [Dataset](https://github.com/pratikkayal/PlantDoc-Dataset)                                       |
| Citrus        | lab         | cls      | disease    | Citrus fruit leaf  | 105 + 609   | 5 + 5    | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919306948?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/3f83gxmv57/2)                                       |
| DiaMOS        | real        | obj      | disease    | Pear fruit leaf    | 499 + 3,006 | 4        | [Paper](https://doi.org/10.5281/zenodo.5557313)                                         | [Dataset](https://doi.org/10.5281/zenodo.5557313)                                                |
| BRACOL        | lab         | obj, seg | disease    | Coffee leaf        | 4,407       | 4        | [Paper](https://arxiv.org/abs/1907.11561)                                               | [Dataset](https://data.mendeley.com/datasets/yy2k5y8mxg/1)                                       |
| RoCoLe        | real        | obj      | disease    | Coffee leaf        | 1,560       | 2        | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919307693?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/c5yvn32dzg/2)                                       |
| PDD271        | real        | cls      | disease    | Multiple           | 220,592     | 271      | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9325065&tag=1)             |                                                                                                  |
| RiceLeaf2020  | real        | cls      | disease    | Rice leaf          | 5,932       | 4        | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169919326997)            | [Dataset](https://data.mendeley.com/datasets/fwcj7stb8r/1)                                       |
| AppleObj      | lab + real  | obj      | disease    | Apple leaf         | 26,377      | 5        | [Paper](https://cdmd.cnki.com.cn/Article/CDMD-10712-1019901670.htm)                     | [Dataset](https://aistudio.baidu.com/aistudio/datasetdetail/11591)                               |
| GoodCorn      | lab         | cls      | disease    | Corn leaf          | 4,117       | 2        |                                                                                         | [Dataset](https://www.kaggle.com/datasets/rabbityashow/corn-leaf-diseasesnlb)                    |
| PDDB          | lab + real  |          | disease    | Multiple           | 50,000      | 171      | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511018307797)            | [Dataset](https://www.digipathos-rep.cnptia.embrapa.br/jspui/)                                   |
| PlantCLEF2022 | real        | cls      | plant      | Multiple Multiple  | 2,885,052   | 80,000   | [Paper](https://www.aicrowd.com/challenges/lifeclef-2022-plant#citations)               | [Dataset](https://www.imageclef.org/PlantCLEF2022)                                               | 
| MEW2014       | lab         | cls      | woody      | Multiple leaf      |             | 151      | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511013000731)            | [Dataset](http://zoi.utia.cas.cz/node/662)                                                       | 
| IP102         | real        | cls, obj | pest       |                    | 75,000      | 102      | [Paper](https://ieeexplore.ieee.org/document/8954351)                                   | [Dataset](https://github.com/xpwu95/IP102)                                                       |
| GWHD          | real        | obj      | wheat head | wheat head         |             |          | [Paper](https://arxiv.org/abs/2005.02162)                                               | [Dataet](https://www.kaggle.com/competitions/global-wheat-detection/data)                        |
| LWDCD2020     | real        | cls      | disease    | wheat spike leaf   | 12,160      | 10       | [Paper](https://www.sciencedirect.com/science/article/pii/S2352914821001313)            | [Dataset](https://github.com/lakshaygoyal425/Wheat-Disease-Detection)                            |
| example       |             |          |            |                    |             |          |                                                                                         |                                                                                                  |                                                                                                   |

 
## Backup
* [python library for food, agriculture](https://github.com/Project-AgML/AgML)
* [China agricultural disease and pest dataset but not available](http://www.icgroupcas.cn/website_bchtk/tuku_jiangdou.html)
* [Grape disease](https://link.springer.com/chapter/10.1007/978-3-031-06430-2_32)
* [PlantifyDr software](https://www.kaggle.com/datasets/lavaman151/plantifydr-dataset)
* [Ariel image](https://arxiv.org/pdf/2004.09754.pdf)
* [ICL plant woody identification](https://ieeexplore.ieee.org/document/6257486)


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
