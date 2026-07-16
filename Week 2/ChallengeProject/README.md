# Challenge Project for Week 2

Sleep data challenge from Massachusetts General Hospital’s (MGH), Computational Clinical Neurophysiology Laboratory (CCNL), and the Clinical Data Animation Laboratory (CDAC): https://www.physionet.org/physiobank/database/challenge/2018/

## Challenge Notebooks
- `Sleep_Analysis_Challenge.ipynb` contains the main challenge notebook and example workflow.
- `Sleep_Analysis_Challenge_Pytorch.ipynb` contains the PyTorch version of the challenge workflow.

Students work with segments of signals from electroencephalography, electrooculography, electromyography, respiratory airflow, and electrocardiography. From these segments they must predict whether the patient was in an aroused (awake), in non-REM1, non-REM2, non-REM3, or REM state.

## Preprocessing
- `Preprocessing.ipynb` contains code that was used to preprocess the data for this challenge.

## Sleep_Analysis_Challenge_Eval_Script
- Script for evaluating challenge submissions from the students. Evaluation metrics include ROCAUC and MCC.

## TEST_LABELS
- Contains the ground truth labels for the test data. This is used to evaluate the results of a model after it has been submitted by students.

Created by Brian Xia
