# Issue-Report-Classification-Using-RoBERTa
This repository contains the notebook for training and testing the classifiers for our participation in the tool competition organized in the scope of the 1st International Workshop on Natural Language-based Software Engineering.

The model is available on [HuggingFace](https://huggingface.co/PeppoCola/IssueReportClassifier-NLBSE22) 

**[Link to Classifier 1 Colab notebook](https://colab.research.google.com/drive/1mgS0fGplVhp_u9h5dAgWo3GkOel9fmrx)**
<br>
**[Link to Classifier 2 Colab notebook](https://colab.research.google.com/drive/1I_MT7tciNnuLcT7zPMHzJjeyY1b-m5DL)**

If you use the software in this repository please consider citing our paper as follows:

```
@inproceedings{Colavito-2022,
  title = {Issue Report Classification Using Pre-trained Language Models},
  booktitle = {2022 IEEE/ACM 1st International Workshop on Natural Language-Based Software Engineering (NLBSE)},
  author = {Colavito, Giuseppe and Lanubile, Filippo and Novielli, Nicole},
  year = {2022},
  month = may,
  pages = {29--32},
  doi = {10.1145/3528588.3528659},
  abstract = {This paper describes our participation in the tool competition organized in the scope of the 1st International Workshop on Natural Language-based Software Engineering. We propose a supervised approach relying on fine-tuned BERT-based language models for the automatic classification of GitHub issues. We experimented with different pre-trained models, achieving the best performance with fine-tuned RoBERTa (F1 = .8591).},
  keywords = {Issue classification, BERT, deep learning, labeling unstructured data,
software maintenance and evolution},
}
```
