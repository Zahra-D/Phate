# PHate Dataset


Welcome to the official repository for our paper titled "Spanning the Spectrum of Hatred Detection: A Persian Multi-Label Hate Speech Dataset with Annotator Rationales", which has been accepted at AAAI24 conference's main track. Here you can find the files for the dataset introduced in our paper, called PHate.

## Overview
PHate is a Persian multi-label hate speech dataset curated for hate speech detection tasks. It includes annotations with annotator rationales, providing valuable insights into the annotators' decision-making process. The dataset comprises 7K data.

## Files
We partitioned the dataset into three segments: training, validation, and test, with proportions of 50%, 40%, and 10% respectively.
- `train_simple.csv`: The training segment of PHate dataset contains tweet IDs, tweet text, and annotated labels.
- `val_simple.csv`: The validaiton segment of PHate dataset contains tweet IDs, tweet text, and annotated labels.
- `test_simple.csv`: The test segment of PHate dataset contains tweet IDs, tweet text, and annotated labels.
- `Dataset_with_span_and_target.csv`: contains targets and annotated spans of hate, encompassing all annotations, even in cases of inconsistency among annotators.

