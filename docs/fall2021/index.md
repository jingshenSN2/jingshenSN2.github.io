# Three Projects (Fall 2021)


## Introduction

In this semester, I took 3 courses as a first year graduate student at Georgetown University: 

 - ANLY 501: Data Science and Analytics
 - ANLY 511: Prob Modeling/Stat Computing
 - ANLY 580: NLP for Data Analytics

Since our program doesn't have final exam, all three courses are ended with a final project. In ANLY 501, I created a portfolio that studied the impact from cryptocurrencies on PC hardware. In ANLY 511, we explored the 2021 Kaggle Data Science and Machine Learning survey to answer our questions about career path. In ANLY 580, we recreated a long form question answering dataset ELI5 and trained an answer generator model on the new dataset. Some records and links below.

## Projects

### 1: PC Hardware & Cryptocurrency in 2021

> The portfolio is hosted at GU domain: [gaojingsong.georgetown.domains/ANLY501](https://gaojingsong.georgetown.domains/ANLY501/1_introduction.html).

This is a big project which spent the whole semester to finish. It included a complete pipeline of telling a data science story including data gathering, data cleaning, EDA, clustering, associate rule mining, and classification(naive Bayes, decision tree, SVM). 

For this project, I would like to say that I'm not very happy with it, because approaches I did in this project were not as deeply as I planned at the beginning. For example, to analyze the relationship between cryptocurrencies and PC hardware, I was expected to perform a time-series regressions, but it turned out that I only did some basic and toy-like classifications on them. Although I don't want to complain about the course, I have to say that the rubrics for this project are very strict, time-consuming, and not applicable for my topic. Even so, there was still some interesting findings from my data and the project was comprehensive that covered most methods we need in a data science research. 

![](/images/posts/fall2021/project1.png)

### 2: Data Science Career Paths & Skillsets in 2021

> The project report is published at team website: [kaggle-ml-survey](https://celeritasml.github.io/kaggle-ml-survey/).

In October, Kaggle published its annually survey[^1] about data science and machine learning. In this project, @Rui Qiu and @Ercong Luo and I explored the responses from this survey and tried to give advice about career path to our peers using statistics, visualizations, hypothesis tests, and multiple linear regressions.

By using 2650 responses, we were able to reconstruct an overview of DS/ML-related jobs in the US. Also, thanks to Rui's expertise in R visualization and Markdown Template, our report is pretty fancy and figures in it are very professional. 

![](/images/posts/fall2021/project2.png)

[^1]: [2021 Kaggle Machine Learning & Data Science Survey.](https://www.kaggle.com/c/kaggle-survey-2021)

### 3: A Long-form Question Answering Model on `ELI5-Category`

> The project report is published at team website: [eli5-category](https://celeritasml.netlify.app/posts/2021-12-01-eli5c/).

Long-form question answering(LFQA) is a relatively new research field in NLG that the model takes a short question but output a long answer. Facebook published a dataset for this task in 2019 called ELI5, but there were some issues like training/validation overlapping in this dataset. In this project, @Qingren Zhou, @Rui Qiu and I tried to create a new categorized version of the ELI5 dataset named as `ELI5-Category`. The additional category labels for each question help us to completely git rid of the overlapping issue.

Also, we trained a two-stage LFQA model with a BERT-like document retriever and a BART-like answer generator. I'd like to say that this model is one of the coolest things I created this year. Here is [Rui's demo video](https://www.youtube.com/watch?v=XGEBU51gr00) showing the model asking questions.

![](/images/posts/fall2021/project3.png)

Credit: [Darren Lebeuf](http://landoflebeef.com/blog/2013/4/24/bert-and-bart)

