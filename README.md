# Real-time Classification and Span-based Detection of Comments on Facebook Sales Posts
## Introduction
We build a data set ViCCSP for the comment classification problem based on user intent, along with the ViSDC dataset for named entity recognition task. The ViCCSP dataset includes five labels (question, order, judge, spam, other), collected from sales posts in social networking groups on Facebook. The ViSDC dataset consists of four entities (phone number, quantity, product, and address). We build real-time systems for streaming data collection, training, and visualization. In this paper, we use Kafka language models for system implementation. PhoBERT-base gives the highest results in task 1 (comment classification), reaching 91.15\% for measuring accuracy and 87.24\% for measuring F1 scores. For task 2 (NER), XLM-RoBERTa-large gives the highest results, reaching 96.03\% - accuracy, 94.37\% - F1 at the word level, 94.77\% - accuracy, 89.39\% - F1 at the span level, 82.88\%-strict. In addition, we have implemented the system and satisfied the users.
## Example of ViCCSP dataset 
<img width="1118" alt="ViCCSP Example" src="https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/c7cb2c49-3032-4716-bd6a-ae17ffdb21b2">

## Example of ViSDC dataset

<img width="693" alt="NER-Example" src="https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/f3c4b1bb-ee55-45fa-9202-0c736e6c2a11">
