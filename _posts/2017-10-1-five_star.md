---
layout: post
title: What Makes a Five Star Food Reiew?
---

#What Makes a Five Star Food Review?
  
Summary: To explore unsupervised learning and NLTK, I wanted to base my project off of one of my favorite things in the 
world... FOOD! As the former editor of my college newspaper's food section, I'm fascinated by how people talk about food 
and how people describe good food versus bad food. This project used natural language processing on Amazon Fine Food 
reviews to reveal which types of food and which qualities of food score the highest reviews to give insight on which 
products Amazon should buy more.  
  
### What Do People Really Want?  
Unfortunately, I can't answer that question in its entirety. But, I'll focus on something we all have in common: 

![Alt Text](https://media.giphy.com/media/ef61oIGVyckY8/giphy.gif)

That's right, food! I will attempt to answer what people *seem* to want in the their Amazon Food Orders.  

### The Data  

I obtained the data set through a recent [kaggle competition](https://www.kaggle.com/snap/amazon-fine-food-reviews). It
contained 500,000 Amazon Fine Food reviews. Because my question focuses on what qualities people are looking for in food, 
I only looked at reviews that received five stars. That narrowed my data set to 363,122 reviews. For efficiency's sake 
(and because my computer is running low on memory), I sampled the data to leave me with 5,000 reviews.  

### Analysis  

I practiced the skills I learned at Metis by using NLTK such as word tokenizing, sentence tokenizing, and parts of speech
tagging. I also used bigrams, which breaks down the text into popular two word phrases to get a birds eye view of the text.  

The most interesting analysis I performed on that text was clustering the reviews. I clustered the reviews to get an idea of 
the types of reviews that are posted in the Amazon Five Star Category. Which begs the question: which food categories are the
most prominent in five star reviews?  
  
Perhaps unsurpisingly, the foods that generate happiness for us overall are the foods that we give five star reviews. 
The top specific categories I encountered were sweets, coffee, dog food, and tea. Which makes sense - how can you not smile 
when you see these gifs or hear this [Shirley Temple song](https://www.youtube.com/watch?v=WLLSqpYyPD8)?

![Alt Text](https://media.giphy.com/media/FKNRErpZ0xoas/giphy.gif)

![Alt Text](https://media.giphy.com/media/mokQK7oyiR8Sk/giphy.gif)  
  
I'm not going to even try to compete with those beautiful dogs, so that's where I'll stop for today.
