---
title: Predictive analytics for healthcare applications   
subtitle: The beauty of a supervised machine learning model

# Summary for listings and search engines
summary: The applications of a machine learning model for healthcare applications.

# Link this post with a project
projects: []

# Date published
date: "2020-04-20T00:00:00Z"

# Date updated
lastmod: "2020-12-13T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Big Data Made Simple**](https://bigdata-madesimple.com/machine-learning-explained-understanding-supervised-unsupervised-and-reinforcement-learning/)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- Javairia Raza

tags:
- Academic

categories:
- Demo
---

Supervised machine learning techniques are a powerful way to look at data. These ML models have a great place in the healthcare world and considering all the data that is collected due to the strict documentation guidelines that the healthcare team have to follow, the possibilities are only limited to when the data can be made available. This blog post will cover different components of the data needed to apply supervised machine learning and the two types of supervised machine learning problems, classification and regression as well as some simple examples of its applications. 

But first lets’ discuss why machine learning can be applied in healthcare. This example is an oversimplification of the problem but is a good illustration to use. Suppose you have a person that has just been admitted to the hospital and based on their co-morbidities, age, sex and specific lab work conducted at admission, you are able to predict how likely they are to get a healthcare associated infection or disease such as sepsis, pneumonia or delirium. This is critical because such conditions are preventable, have serious consequences for health and wellbeing of the patient (if unmanaged, it can even lead to death) and also has huge economic costs to the healthcare system as it leads to extended stay, more resources (staff, beds, supplies) (1). 

But what do we need to do for supervised machine learning models? In a supervised machine learning model, the data needs to have features and a column for the target. For example, if we are trying to predict whether a person has diabetes, we would measure their blood glucose and insulin level to make a judgement. The lab measurements would be the features and the diabetes diagnosis would be the target. A machine learning model will take the features and try to learn from the data to detect patterns based on the target. This is called training the model. Next, you go through a series of rigrous steps to optimize the model algorithm that has seen the data by fine tuning some of its parameters or even fine tuning the data itself. Once this process is complete, you can show the model a new example that it has not seen yet and it will output the class of the target. Using the diabetes example from before, if we were to pass the model a new person’s lab work results, it would be able tell us whether the person has diabetes or not.

What has been described above is one type of a supervised problem called classification. In classification problems, the target classes can be thought of as groups. If the target column is diabetes diagnosis, there are two classes, person has diabetes or person does not have diabetes. There can be more than two classes which would be called a multi classification problem. But what if your target column is a numeric quantity rather than a class/category. In that case, you would have a regression problem. In this problem, the model outputs a numeric real number such as predicting the life expectancy of a patient based on a specific set of characteristics (2).

Alongside supervised machine learning, there are other branches of machine learning ways known as unsupervised machine learning and reinforcement learning. When to use what depends on the context and the problem you are trying to solve. The data that you use does not have to tabular quantitative data only. ML models can work with text, images, videos and audio as well. In conclusion, supervised machine learning has huge possibilities in the healthcare world and its applications can greatly improve the quality and delivery of care for patients. 

## References:

1. https://health.gov/our-work/health-care-quality/health-care-associated-infections

2. https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-019-0681-4

3. https://bigdata-madesimple.com/machine-learning-explained-understanding-supervised-unsupervised-and-reinforcement-learning/

