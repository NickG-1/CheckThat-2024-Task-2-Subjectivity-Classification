# CheckThat-2024-Task-2-Subjectivity-Classification
This repository contains the code and data for an approach to the [CheckThat! 2024 Task 2](https://checkthat.gitlab.io/clef2024/task2/): Subjectivity Classification. The task is to determine whether a sentence from a news article is subjective or objective.
The system in this repository is specifically designed for the English language.

## Structure of this repository
- `data/`: Contains the training and test data.
- `main.ipynb`: The main notebook that contains the code for the system.
- `evaluation/`: Contains the score and metrics for different models and parameters. `evaluation.tsv` contains the score for different models, preprocessing techniques, and features. `paratuningLinReg.tsv` contains the scores for parameter optimization of the Logistic Regression model. `paratuningSVM.tsv` contains the scores for parameter optimization of the SVM model. `resultTest.txt` contains the scores and metrics for the dev_test and test data. Both datasets have only been used for the final evaluation of the system and were only run once.
- `documentation/`: Contains slides documenting the system.

## Reproducing the results
To reproduce the results stated in the documentation you just have to run `main.ipynb`.
