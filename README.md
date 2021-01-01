# VQA BoWIE: Bag of Words Image Explanation


## Data missing in repo

* [VQA_image_features.h5](https://github.com/timbmg/NLP1-2017-VQA/blob/master/data/Readme.md) - pretrained CNN features (you don't need actual images)
* [glove.6B.300d.txt](https://nlp.stanford.edu/projects/glove/) - word embeddings
* [v2_Annotations_Train_mscoco.zip](https://visualqa.org/download.html) - answers data & more
* [v2_Questions_Train_mscoco.zip](https://visualqa.org/download.html) - questions data, images ids & more

## Project Structure
<pre>
.
├── Data
│   ├── Additional
│   │   ├── VQA_image_features.h5 (absent)
│   │   ├── image_ids_vqa.json
│   │   ├── imgid2imginfo.json
│   │   └── VQA_img_features2id.json
│   ├── GloVe
│   │   └── glove.6B.300d.txt (absent)
│   ├── Subset
│   │   └── (empty)
│   └── VQA_Train
│       ├── v2_Annotations_Train_mscoco.zip (absent)
│       └── v2_Questions_Train_mscoco.zip (absent)
├── Gallery
│   └── (some pics)
├── Notebooks
│   ├── scripts
│   │   └── (empty)
│   ├── DataPreparation.ipynb
│   ├── EmbeddingPreparation.ipynb
│   ├── Preprocessing.ipynb
│   └── TrainBOWIMG.ipynb
├── README.md
└── Weights
    └── 30.5.pt
</pre>

## Todo

* Pure BoW vs W2V comarison
* Linear Layer matrix splitting into textual and visual parts
* Different metrics instead of a silly accuracy
* Data statistics
* Make sure the same pics ids don't end up in the same train/valid/test split
* Different questions for the same picture, vise versa
* Score > 30% ?
* Good README with references

## Demo
![alt text](https://github.com/McCastles/BoWIE/blob/main/Gallery/1.png "1")

![alt text](https://github.com/McCastles/BoWIE/blob/main/Gallery/2.png "2")

![alt text](https://github.com/McCastles/BoWIE/blob/main/Gallery/3.png "3")

![alt text](https://github.com/McCastles/BoWIE/blob/main/Gallery/4.png "4")

