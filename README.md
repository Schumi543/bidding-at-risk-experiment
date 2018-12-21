this source copy from https://www.dropbox.com/sh/mhc9os8c5anf0tw/AABuXdGesR_DGi3CbgN32qhGa?dl=0

- paper: https://dl.acm.org/citation.cfm?id=3018701
- supplementary materials: https://www.dropbox.com/s/qpv82dtrvdhk4zb/supplementary.pdf?dl=0

The oridinal README.txt is as follows.

```
# bidding-at-risk-experiment


This repository includes experiment code for two risk-aware bidding strategies.



For repeating the experiment, please follow these steps:



i) Download iPinYou datasets from http://data.computational-advertising.org/.



ii) Prepare data following https://github.com/wnzhang/make-ipinyou-data.



iii) Use remove-pinyou-tag.py to remove tag information from datasets.



iv) Use lryzx.py to train LR models for each campaign.



v) Use divide-pinyou-test-data.py to split test data into two equal parts.



vi) Use lap-bayes.py to train CTR distribution model.



vii) Use replay-lr.py, replay-rmr.py, replay-var.py to replay validation test with the baseline and the two risk-aware strategies.



viii) Use select-parameters.py to select model hyperparameters from replay results.



ix) Use experiment.py to replay test data and obtain final results. 

```
