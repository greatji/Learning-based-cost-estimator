# Learning-based-cost-estimator

Source code of Feature Encoding and Model Training for cardinality and cost estimation based on PostgreSQL Execution Plans.
The tree-structured model can generate representations for sub-plans which could be used by other query processing tasks like Join Reordering,
Materialized View and even Index Selection.

### Unitest
```bash
export PYTHONPATH=code/
python -m unittest code.test.test_feature_extraction.TestFeatureExtraction
python -m unittest code.test.test_feature_encoding.TestFeatureEncoding
python -m unittest code.test.test_training.TestTraining
```

### Datasets
For Nemerical workload: https://github.com/andreaskipf/learnedcardinalities  

For Complete JOB: https://pan.baidu.com/s/14ZN1DqRcTOJJqsi8203suw  password: tt2s

### Citation
If you use the code in your work, please cite our paper.  
```
@article{DBLP:journals/pvldb/SunL19,
  author    = {Ji Sun and
               Guoliang Li},
  title     = {An End-to-End Learning-based Cost Estimator},
  journal   = {{PVLDB}},
  volume    = {13},
  number    = {3},
  pages     = {307--319},
  year      = {2019},
  url       = {http://www.vldb.org/pvldb/vol13/p307-sun.pdf},
  doi       = {10.14778/3368289.3368296},
  timestamp = {Wed, 04 Dec 2019 19:13:52 +0100},
  biburl    = {https://dblp.org/rec/bib/journals/pvldb/SunL19},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

### Contact
If you have any issue, feel free to post on [Project](https://github.com/greatji/Learning-based-cost-estimator).
