# Precog Recruitment Task

## Task: Analyzing hateful memes || Theme: Computer Vision

- Name: Swayam Agrawal
- Roll: 2021101068
  
----

## Directory Structure
```
.
├── README.md
├── hateful_memes
│   ├── data
│      ├── dev_seen.jsonl
│      ├── dev_unseen.jsonl
│      ├── test_seen.jsonl
│      ├── test_unseen.jsonl
│      ├── train.jsonl
│      └── img (not included in repo)  
├── code.ipynb
├── bonus.ipynb
├── report.pdf
├── Image-Embedding.csv
├── Text-Embeddings.csv
├── Image-Embedding-Test.csv
├── Text-Embeddings_test.csv
└── yolov8m.pt 
```

----

`code.ipynb` contains the code for the main task:
  - Object Detection
  - Caption Impact Assessment
  - Classification System Development

`bonus.ipynb` contains the code for the bonus task:
  - Sentiment Analysis

`report.pdf` contains the report for the main task. The notion page for the report is live on the web and can be found [here](https://acoustic-art-669.notion.site/Precog-Task-Report-028caca7e5aa481e8007481e05aa8473?pvs=4).

`Image-Embedding.csv` and `Text-Embeddings.csv` contain the embeddings for the training data.

`Image-Embedding-Test.csv` and `Text-Embeddings_test.csv` contain the embeddings for the test data.

`yolov8m.pt` contains the weights for the YOLOv8m model used for object detection.

----

## Instructions to run the code
- Clone the repository
- The `img` folder for the hateful memes dataset is not included in the repository and can be downloaded from [here](https://hatefulmemeschallenge.com/). Add the `img` folder to the `data` folder in the `hateful_memes` directory.
- Run the `code.ipynb` notebook for the main task.
- Run the `bonus.ipynb` notebook for the bonus task.