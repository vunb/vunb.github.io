---
layout: page
title: Chatbot FAQ
category: chatbots
tags: tensorflow chatbots word-embeddings seq2seq
---

![chatbots and deep learning](/img/chatbots-and-deep-learning.jpg)

# [How to train tensorflow chat application on updated dataset everyday?](https://datascience.stackexchange.com/a/18899)

**Q**: I have created chatbot on **Cornell** movie dataset and it's working fine. I have trained chatbot application up to global step 330000. I am using tensorflow library. I am also receiving output fine. Then I created this new dataset file by modifying original dataset and i wish to train chatbot application with updated files. Now should I delete previously saved checkpoints and saved data and start training from zero or should i train from 330000 onwards without worrying changes in dataset. I wish to modify database daily basis and train on modified database. Please kindly let me know if you have a suggestion for me as I am stuck on this issue. I will really appreciate if you help me with this issue.

**A**: The distribution of your data won't change too much over a smaller period of time, retraining from scratch seems like a waste. Just add the new data to your set and do one or more epochs on all your data, not just the new ones. It can readjust the weights a little bit for changes in the distribution which is exactly what you want. Make sure you are not overreliant on early stopping as regularization method against overfitting because you continuously train like this, use some other regularizer. I would suggest periodically to retrain from scratch but this doesn't have to happen very regularly, maybe once every two months.

Source: [https://datascience.stackexchange.com/a/18899](https://datascience.stackexchange.com/a/18899)

