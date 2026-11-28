# <p align="center"><a href="https://www.kaggle.com/ruddyguerreroalvarez">Kaggle competitions</a></p>

Kaggle is a free platform that provides users with a series of problems to solve with topics such as:

* Data science.
* Predictive analytics.
* Machine learning.

This repository is a collection of my answers to Kaggle problems.

<p align="center">
  <img src="img/kaggle.jpg" width="100%" height="auto">
</p>

## Competitions

| Competition | Approach | Score | Notebook |
|-------------|----------|------:|----------|
| [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer) | Ensemble of 7 CNNs with data augmentation | 99.453% public (99.5% validation) | [notebook](Digit%20Recognizer/digit-recognizer-ensemble-of-7-cnns-keras-3.ipynb) |

## Data

Competition data is not committed to this repository: Kaggle's competition rules do not allow redistributing it, and the files are large. Download it with the [Kaggle CLI](https://github.com/Kaggle/kaggle-api) into each competition's `Data/` folder:

```bash
pip install kaggle
kaggle competitions download -c digit-recognizer -p "Digit Recognizer/Data"
unzip "Digit Recognizer/Data/digit-recognizer.zip" -d "Digit Recognizer/Data"
```

You need to accept the competition rules on Kaggle and have an API token in `~/.kaggle/kaggle.json`.
