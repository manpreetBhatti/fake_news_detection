# Fake News Detection Using Sentence Embedding

## Background and Context 

Fake news is increasingly being utilized to influence public opinion and political processes. This has been made possible by existing infrastructure and online media platforms (e.g., Facebook, Twitter) that make information dissemination simple. Information can be published on sites and shared among users through social media platforms without the need for third-party filtering or fact-checking, unlike traditional print media. Given that 62% of adults in the United States acquire their news from social media, and many people who encounter bogus stories believe them, these platforms have become a target for disinformation campaigns. Fake news has received much attention, the problem is still poorly understood. It's difficult to find and cross-reference contradictory sources and assertions. Due to the increasing number of news sites and high content volume, the situation is worsened. Automated approaches that identify potentially fake news and untrustworthy news sources can improve manual factchecking by providing contextual information and minimizing the amount of content that a human fact-checker must analyse. Such tools can also help us better understand the false news ecosystem: where it begins, how it spreads, and how to counteract its consequences


## Problem Statement 

To correctly identify the nature of the news by getting by adding a new layer to our deep learning model that will strengthen its classification power. Embedding (sentence, word or graph) can help us derive the sentiment or the semantics of the sentences and allow us to use it for news classification. If our model is able to perceive and understand the information the news piece is trying to convey then we will be able to catch fake news faster. 

## Research Questions 

In this project we will try and answer the following questions: 
1)	To use sentence embedding and get the vectors representing the meaning of the sentences in the news piece. 
2)	To build the model that will intake the vectors and use it as feature to accurately detect the nature of the news piece.

## Dataset used for training and testing

**https://www.liebertpub.com/doi/10.1089/big.2020.0062**

