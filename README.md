## Key points
* Objectives: recognize the plant disease on plant leaf and fruit using RGB images
* Tasks: image classification (cls), object detection (obj), segmentation (seg) 

## Datasets

| Name                 | Description        | Plant type            | # img       | # class | Task     | Paper                                                                                   | Dataset                                                                                 |
|----------------------|--------------------|-----------------------|-------------|---------|----------|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| Plant Pathology 2020 | Field              | Apple leaf            | 3,642       | 3       | cls      | [Paper](https://bsapubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aps3.11390)       | [Dataset](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data)          |
| Cassava              | Field              | Cassava leaf          | ~15,000     | 5       | cls      |                                                                                         | [Dataset](https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data) |
| PlantVillage         | Lab                | Multiple leaf         | 54,305      | 38      | cls      | [Paper](https://arxiv.org/abs/1511.08060)                                               | [Dataset](https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color)      |
| Cucumber             | Field              | Cucumber leaf         |             | 2       | cls      |                                                                                         |[Dataset](https://www.kaggle.com/datasets/kareem3egm/cucumber-plant-diseases-dataset)|
| PlantifyDr           | Data aug, software | PlantVillage          |             |         | cls      |                                                                                         | [Dataset](https://www.kaggle.com/datasets/lavaman151/plantifydr-dataset)                |
| PlantDoc             | Field              | Multiple              |             |         | cls, obj | [Paper](https://dl.acm.org/doi/pdf/10.1145/3371158.3371196)                             | [Dataset](https://github.com/pratikkayal/PlantDoc-Dataset)                              |
| Citrus               | Lab                | Citrus fruit + leaf   | 105 + 609   | 5 + 5   | cls      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919306948?via%3Dihub)                                                                               | [Dataset](https://data.mendeley.com/datasets/3f83gxmv57/2)                              |
| DiaMOS               | Field              | Multiple fruit + leaf | 499 + 3,006 | 4       | obj      | [Paper](https://doi.org/10.5281/zenodo.5557313)                                         | [Dataset](https://doi.org/10.5281/zenodo.5557313)                                       |
| BRACOL               | Lab                | Coffee leaf           | 4,407       | 4       | obj      | [Paper](https://arxiv.org/abs/1907.11561)                                               | [Dataset](https://data.mendeley.com/datasets/yy2k5y8mxg/1)                              |
| RoCoLe               | Field              | Coffee leaf           | 1,560       | 2       | obj      | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340919307693?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/c5yvn32dzg/2)                              |
| No                   | Very big dataset   | Multiple              | 220,592     | 271     | cls      | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9325065&tag=1)             |No|


## Papers
| Name | Year | Source             | Description                              | Dataset         | Paper                                                                        |
|------|------|--------------------|------------------------------------------|-----------------|------------------------------------------------------------------------------|
|      | 2022 | Com and Elc on agr | Supervised transfer learning             | Plant Villiage  | [Paper](https://www.sciencedirect.com/science/article/pii/S0168169922000205) |
|      | 2021 | Plant Methods      | Semi-supervised, few-shot, self-training | Plant Village   | [Paper](https://link.springer.com/article/10.1186/s13007-021-00770-1)        |
|      |      |                    |                                          |                 |                                                                              |
