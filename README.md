# Real-time Classification and Span-based Detection of Comments on Facebook Sales Posts
## Introduction
We build a data set ViCCSP for the comment classification problem based on user intent, along with the ViSDC dataset for named entity recognition task. The ViCCSP dataset includes five labels (question, order, judge, spam, other), collected from sales posts in social networking groups on Facebook. The ViSDC dataset consists of four entities (phone number, quantity, product, and address). We build real-time systems for streaming data collection, training, and visualization. In this paper, we use Kafka language models for system implementation. PhoBERT-base gives the highest results in task 1 (comment classification), reaching 91.15\% for measuring accuracy and 87.24\% for measuring F1 scores. For task 2 (NER), XLM-RoBERTa-large gives the highest results, reaching 96.03\% - accuracy, 94.37\% - F1 at the word level, 94.77\% - accuracy, 89.39\% - F1 at the span level, 82.88\%-strict. In addition, we have implemented the system and satisfied the users.
## Example
### ViCCSP dataset 
<img width="1118" alt="ViCCSP Example" src="https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/c7cb2c49-3032-4716-bd6a-ae17ffdb21b2">

### ViSDC dataset

<img width="693" alt="NER-Example" src="https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/f3c4b1bb-ee55-45fa-9202-0c736e6c2a11">

## Dataset visualizations
### ViCCSP
![Classification-dataset visualization](https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/090973ac-41d2-487f-9adf-7c6a0ef3caa9)
### ViSDC
![NER-dataset visualization](https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/cf1a204f-ce86-46ec-b341-fb0f36e03b7f)

## Model Performance
### ViCCSP
<img width="514" alt="Classification Performance" src="https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/babe0293-3f03-4b50-ac1a-613ea73f28cd">

### ViSDC
<img width="643" alt="NER-Performance" src="https://github.com/duyngoc-adn/ViCCSP_ViSDC/assets/73750674/4d58c0ad-7c8b-4436-90e0-e88d50822a84">

## Contact
Authors:
Tam Huu Minh Nguyen, Tinh Pham Phuc Do, Ngoc Dinh Duy Cao, The Tran Gia Nguyen, and Trong-Hop Do

Faculty of Information Science and Engineering, University of Information Technology, Ho Chi Minh City, Vietnam

Vietnam National University, Ho Chi Minh City, Vietnam

{20521871,20522020,20521661,20521940}@gm.uit.edu.vn and hopdt@uit.edu.vn
