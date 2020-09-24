---
layout: post
title:  "Natural Language Processing and spaCy"
date:   2020-09-24
categories: rpa-tomorrow blog 
---
Greetings!

This project builds around that a computer in some way understanding human text and some form of what the human want. The process of tokenizing, tagging and labeling text is known as Natural Language Processing and there are a plethora of different tools and frameworks open for use.

The one we have chosen for this project is known as spaCy. The creators boast of spaCy as "Industrial-Strength Natural Language Processing in python". The reason we chose this framework is that it has support for multiple languages and a lot of pretrained models. This will hopefully reduce the time needed to develop the NLP pipeline. Compared to more general tools like Pytorch which can be used for multiple different Neural Network problems, spaCy allows for a faster start and less of a learning curve. 

Other nice features is a simple to use tokenizer and part-of-speech tagging. These features exists in other frameworks like NLTK which is a Python toolkit for NLP. NLTK might be competitor to use instead of spaCy but the lack of a neural network in NLTK would limit the usability in our usecase. 

For our needs and constrains spaCy seems like the optimal tool to build upon, paving the way to a working prototype without the need to spend all resources on the text processing.

/The RPA Tomorrow Team

[rpa-repo]: https://github.com/rpa-tomorrow/substorm-nlp
