## Key points
* Objectives: recognize the plant disease on plant leaf and fruit using RGB images
* Foliar disease
* Tasks: image classification (cls), object detection (obj), segmentation (seg) 

## Datasets

| Name                 | Description                        | Plant type                 | # img          | Resolution | # class | Task     | Paper                                                                                   | Dataset                                                                                 |
|----------------------|------------------------------------|----------------------------|----------------|------------|---------|----------|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| Plant Pathology 2020 | Real sceniaro                      | Apple leaf                 | 3,642          | Single     | 3       | cls      | [Paper](https://bsapubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aps3.11390)       | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data)          |
| Cassava              | Field                              | Cassava leaf               | 21,397 (train) | Single     | 5       | cls      |                                                                                         | [Dataset](https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data) |
| PlantVillage         | Lab                                | Multiple leaf              | 54,305         | Single     | 38      | cls      | [Paper](https://arxiv.org/abs/1511.08060)                                               | [Dataset](https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color)      |
|                      | Real sceniaro, image may not clear | Cucumber leaf              | 691            | Single     | 2       | cls      |                                                                                         | [Dataset](https://www.kaggle.com/datasets/kareem3egm/cucumber-plant-diseases-dataset)   |
| PlantifyDr           | Public software                    |                            |                |            |         |          |                                                                                         | [Dataset](https://www.kaggle.com/datasets/lavaman151/plantifydr-dataset)                |
| PlantDoc             | Internet                           | Multiple                   | 2,598          | Multiple   | 17      | cls, obj | [Paper](https://dl.acm.org/doi/pdf/10.1145/3371158.3371196)                             | [Dataset](https://github.com/pratikkayal/PlantDoc-Dataset)                              |
| Citrus               | Lab                                | Citrus fruit + leaf        | 105 + 609      | Single     | 5 + 5   | cls      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919306948?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/3f83gxmv57/2)                              |
| DiaMOS               | Real sceniaro                      | Pear fruit + leaf          | 499 + 3,006    | Multiple   | 4       | obj      | [Paper](https://doi.org/10.5281/zenodo.5557313)                                         | [Dataset](https://doi.org/10.5281/zenodo.5557313)                                       |
| BRACOL               | Lab                                | Coffee leaf                | 4,407          | Single     | 4       | obj, seg | [Paper](https://arxiv.org/abs/1907.11561)                                               | [Dataset](https://data.mendeley.com/datasets/yy2k5y8mxg/1)                              |
| RoCoLe               | Real sceniaro, leveld severity     | Coffee leaf                | 1,560          | Single     | 2       | obj      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919307693?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/c5yvn32dzg/2)                              |
| PDD271               | Real sceniaro                      | Multiple                   | 220,592        |            | 271     | cls      | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9325065&tag=1)             | No                                                                                      |
| Plant_CLEF2022       | Real sceniaro                      | Multiple fruit+leaf+flower | 2,885,052      | Similar    | 80,000  | cls      | [Paper](https://hal.inrae.fr/hal-03353469/file/Goeau_etal_CLEF_2021.pdf)                | [Dataset](https://www.imageclef.org/PlantCLEF2022)                                      |
|                      | Real sceniaro + Internet           | Rice leaf                  | 5,932          | Single     | 4       | cls      | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169919326997)            | [Dataset](https://data.mendeley.com/datasets/fwcj7stb8r/1)                              |
|                      | Lab + Real sceniaro                | Apple leaf                 | 26,377         | Single     | 5       | cls      | [Paper](https://cdmd.cnki.com.cn/Article/CDMD-10712-1019901670.htm)                     | [Dataset] (https://aistudio.baidu.com/aistudio/datasetdetail/11591)|
## Papers
| Name | Year | Source             | Description                                                            | Dataset         | Paper                                                                        |
|------|------|--------------------|------------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------|
|      | 2022 | Com and Elc on agr | Supervised transfer learning                                           | Plant Village  | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169922000205) |
|      | 2021 | Plant Methods      | Supervised transfer learning, Semi-supervised, few-shot, self-training | Plant Village   | [Paper](https://link.springer.com/article/10.1186/s13007-021-00770-1)        |
|      |      |                    |                                                                        |                 |                                                                              |


## backup
* [China 农业病虫害研究图库](http://www.icgroupcas.cn/website_bchtk/tuku_jiangdou.html)
* [apple leaf](https://aistudio.baidu.com/aistudio/datasetdetail/76075)
* [wheat leaf](https://www.sciencedirect.com/science/article/pii/S2352914821001313)

## Other related dataset (not leaf diease)

| Name         | Description | Plant type | # img | Resolution | # class | Task | Paper                                                                                                                                                                             | Dataset                                     |
|--------------|-------------|------------|-------|------------|---------|------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------|
| MEW2012 Leaf | Lab         | Multiple   |       |            |         |      | [Paper](https://www.sciencedirect.com/science/article/pii/S1537511013000731)                                                                                                      | [Dataset](http://zoi.utia.cas.cz/node/662)  |
 | ICL Leaf     |             |            |       |            |         |      | [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6257486&casa_token=kvGjTUmzsJMAAAAA:Y9E9MCN5eGcKJ1PVMUVKoKH9JyrGPbkqPG4IThgcfdlq1Db91OMvy6JuscmcielhyUoRXGnDXDA)     | [Dataset]                                   |
