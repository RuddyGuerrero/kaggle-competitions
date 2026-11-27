# <p align="center"><a href="https://www.kaggle.com/c/digit-recognizer/overview">Digit Recognizer</a></p>

<p align="center">
  <img src="img/numbers2.png" width="100%" height="auto">
</p>

## **Competition Description**

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.


## Data

Download the competition data into `Data/` before running the notebook (see the [root README](../README.md#data)):

```bash
kaggle competitions download -c digit-recognizer -p "Digit Recognizer/Data"
```

The notebook reads the data from `/kaggle/input/competitions/digit-recognizer/`, where Kaggle mounts it once the competition is added with **+ Add Input**. To run it locally, change the paths in the loading cell to `Data/`.
