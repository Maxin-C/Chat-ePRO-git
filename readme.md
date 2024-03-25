# Chat-ePRO Respository
This respository store the dataset example and codes used in the construction of Chat-ePRO.

The `code` folder contains the model training and testing code for BERT models on three downstream tasks: multi-label classification, semantic matching, and contrastive learning. 
**Attention**: The dataset is not provided, so the models cannot be trained and tested.

The `corpus example` folder contains datasets for BIBCQ, FACT-B, and TMI forms after being annotated. Each file includes three examples. The first two examples in each file are used for multi-label classification and semantic matching, as these two downstream tasks share the same dataset structure in this study. The last example contains positive and negative samples for contrastive learning, used for fine-tuning its model.

The `forms` folder contains the content of the three forms in Chinese. This is the data structure used in our experiment.

The `results` folder contains an Excel that display FP, FN, TP, ACC, P, R and F1 results of five downstream tasks. 