## Template datasets
* basic information about the dataset
* number of images and their class name
    * use: ```find . -type f | cut -d/ -f2 | sort | uniq -c```



## PlantVillageDataset
* 38 classes
* 14 plants
* taken in lab with uniform backgrounds
* number of images and their class name
```angular2html
630 Apple___Apple_scab
621 Apple___Black_rot
275 Apple___Cedar_apple_rust
1645 Apple___healthy
1502 Blueberry___healthy
854 Cherry_(including_sour)___healthy
1052 Cherry_(including_sour)___Powdery_mildew
513 Corn_(maize)___Cercospora_leaf_spot Gray_leaf_spot
1192 Corn_(maize)___Common_rust_
1162 Corn_(maize)___healthy
985 Corn_(maize)___Northern_Leaf_Blight
1180 Grape___Black_rot
1383 Grape___Esca_(Black_Measles)
423 Grape___healthy
1076 Grape___Leaf_blight_(Isariopsis_Leaf_Spot)
5507 Orange___Haunglongbing_(Citrus_greening)
2297 Peach___Bacterial_spot
360 Peach___healthy
997 Pepper,_bell___Bacterial_spot
1478 Pepper,_bell___healthy
1000 Potato___Early_blight
152 Potato___healthy
1000 Potato___Late_blight
371 Raspberry___healthy
5090 Soybean___healthy
1835 Squash___Powdery_mildew
456 Strawberry___healthy
1109 Strawberry___Leaf_scorch
2127 Tomato___Bacterial_spot
1000 Tomato___Early_blight
1591 Tomato___healthy
1909 Tomato___Late_blight
952 Tomato___Leaf_Mold
1771 Tomato___Septoria_leaf_spot
1676 Tomato___Spider_mites Two-spotted_spider_mite
1404 Tomato___Target_Spot
373 Tomato___Tomato_mosaic_virus
5357 Tomato___Tomato_Yellow_Leaf_Curl_Virus
```


## FieldPV
* 38 classes
* 14 plants
* taken in real field
* number of images and their class name
```
33 01Orange___Haunglongbing_(Citrus_greening)
32 02Apple___Apple_scab
19 03Apple___Black_rot
12 04Apple___Cedar_apple_rust
9 05Apple___healthy
12 06Blueberry___healthy
10 07Cherry_(including_sour)___healthy
10 08Cherry_(including_sour)___Powdery_mildew
22 09Corn_(maize)___Cercospora_leaf_spot Gray_leaf_spot
15 10Corn_(maize)___Common_rust_
28 11Corn_(maize)___healthy
17 12Corn_(maize)___Northern_Leaf_Blight
9 13Grape___Black_rot
11 14Grape___Esca_(Black_Measles)
20 15Grape___healthy
12 16Grape___Leaf_blight_(Isariopsis_Leaf_Spot)
20 17Peach___Bacterial_spot
11 18Peach___healthy
13 19Pepper,_bell___Bacterial_spot
9 20Pepper,_bell___healthy
11 21Potato___Early_blight
10 22Potato___healthy
15 23Potato___Late_blight
8 24Raspberry___healthy
23 25Soybean___healthy
25 26Squash___Powdery_mildew
32 27Strawberry___healthy
48 28Strawberry___Leaf_scorch
10 29Tomato___Bacterial_spot
19 30Tomato__Early_blight
11 31Tomato___healthy
28 32Tomato__Late__Blight
17 33Tomato___Leaf_Mold
17 34Tomato___Septoria_leaf_spot
11 35Tomato_Spider_mites Two-spotted_spider_mite
11 36Tomato___Target_Spot
8 37Tomato___Tomato_mosaic_virus
37 38Tomato___Tomato_Yellow_Leaf_Curl_Virus
```


## PlantDoc classification dataset
* 28 classes
* 13 plants
* collect from internet
* numer of images in training dataset
```angular2html
82 Apple leaf
 79 Apple rust leaf
 83 Apple Scab Leaf
 53 Bell_pepper leaf
 62 Bell_pepper leaf spot
106 Blueberry leaf
 47 Cherry leaf
 64 Corn Gray leaf spot
180 Corn leaf blight
106 Corn rust leaf
 57 grape leaf
 56 grape leaf black rot
103 Peach leaf
109 Potato leaf early blight
 97 Potato leaf late blight
112 Raspberry leaf
 57 Soyabean leaf
124 Squash Powdery mildew leaf
 88 Strawberry leaf
 79 Tomato Early blight leaf
 55 Tomato leaf
101 Tomato leaf bacterial spot
101 Tomato leaf late blight
 44 Tomato leaf mosaic virus
 70 Tomato leaf yellow virus
 85 Tomato mold leaf
140 Tomato Septoria leaf spot
  2 Tomato two spotted spider mites leaf
```
* numer of images in testing dataset
```angular2html
  9 Apple leaf
 10 Apple rust leaf
 10 Apple Scab Leaf
  8 Bell_pepper leaf
  9 Bell_pepper leaf spot
 11 Blueberry leaf
 10 Cherry leaf
  4 Corn Gray leaf spot
 12 Corn leaf blight
 10 Corn rust leaf
 12 grape leaf
  8 grape leaf black rot
  9 Peach leaf
  8 Potato leaf early blight
  8 Potato leaf late blight
  7 Raspberry leaf
  8 Soyabean leaf
  6 Squash Powdery mildew leaf
  8 Strawberry leaf
  9 Tomato Early blight leaf
  8 Tomato leaf
  9 Tomato leaf bacterial spot
 10 Tomato leaf late blight
 10 Tomato leaf mosaic virus
  6 Tomato leaf yellow virus
  6 Tomato mold leaf
 11 Tomato Septoria leaf spot
```


## PlantLeaf
* 12 classes and 12 plants
* each plant includes healthy and disease leaf
* numer of images and their class names
```angular2html
433 Alstonia Scholaris (P2)
452 Arjun (P1)
118 Bael (P4)
148 Basil (P8)
223 Chinar (P11)
419 Gauva (P3)
624 Jamun (P5)
257 Jatropha (P6)
236 Lemon (P10)
435 Mango (P0)
559 Pomegranate (P9)
598 Pongamia Pinnata (P7)
```

## TaiwanTomato
* 6 classes for tomato leaf disease
* taken from multiple conditions, lab and real field.
* number of images in training dataset
```angular2html
88 Bacterial spot
 53 Black mold
 67 Gray spot
 84 health
 78 Late blight
125 powdery mildew
```
* number of images in testing dataset
```angular2html
22 Bacterial spot
14 Black mold
17 Gray spot
22 health
20 Late blight
32 powdery mildew
```