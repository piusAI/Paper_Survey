---
layout: post
title: "MaxPool"
date: 2025-06-18
categories: ai paper
tags: [paper, CNN, Maxpool, English study, ai]
author: pius
published: false
cover-img: /assets/img/POSE.jpg
thumbnail-img: /assets/img/PaperThumnail.png
share-img: /assets/img/POSE2.jpg
---

## 📄 Survey Title : Evaluation of Pooling Operations in Convolutional Architectures for Object Recognition

 Paper Link: [(Evaluation of Pooling Operations in Convolutional Architextures for Object Recognition)](https://www.ais.uni-bonn.de/papers/icann2010_maxpool.pdf)


This post is for MaxPooling

---

### 📖 Abstract

> A common practice to gain invariant features in object recognition models is to aggregate multiple low-level features over a small
neighborhood. However, the differences between those models makes
a comparison of the properties of different aggregation functions hard...

---

### 🟨 01. Word Estimate - Label

| Word (t)         | ŷ (예측값)   | Loss |
|------------------------|---------------|------|
| invariant (불변의)        | 다양한          | 0.92 |
| aggregate (모으다, 집합)   | 재귀            | 0.86 |
| aggregation (집합, 모임)  | 회귀            | 0.89 |
| empirical (경험적인)      | 엄청난          | 0.84 |
| outperforms (능가하다)    | 보여준다         | 0.33 |
| improvement (향상)       | 성장            | 0.12 |
| despite (~에도 불구하고) | 그럼에도         | 0.05 |
| jittered-cluttered (흔들리고 어지러운) | - | 1.00 |
| improvement (향상)       | 성장            | 0.12 |
| mammal (포유류)          | -    | 1.00 |
| cortex (대뇌피질)         | -     | 1.00 |
| spatial (공간적인)        | 부분의           | 0.78 |
| assume (가정하다)          | 추측하다         | 0.08 |
| neoconitron (초기 신경망 모델) | - | 1.00 |


Low Loss : 
High Loss : 






---

### 🧠 02. 의미 추론 및 해석 연습

> “Realtime multi-person 2D pose estimation is a key component...”  
→ 영상과 이미지에서 사람을 이해하는 데 중요한 요소는 바로 **실시간으로 여러 사람의 2D 자세를 추정**하는 기술이다.

> “...Part Affinity Fields (PAFs), to learn to associate body parts...”  
→ **PAF라는 비모수적 표현**을 이용해 사람의 **각 신체 부위를 식별하고 연결**한다.

---

### 📘 03. 단어 확인 후 다시 읽기

위에서 정리한 단어들을 확인한 뒤, 전체 abstract를 다시 한 번 천천히 읽어보며 문장의 의미를 정확히 파악합니다.  

---

https://cs.nyu.edu/~yann/research/norb/index.html


### ✅ 04. Summary

> 이 논문은 이미지 안의 **여러 사람의 자세를 실시간으로 추정하는 알고리즘**을 소개한다.  
> 핵심은 **Part Affinity Fields(PAF)** 라는 방식을 통해 **신체 부위의 연결성을 학습**하고, 이 연결을 바탕으로 각 사람의 자세를 파악하는 것이다.  
> bottom-up 방식이므로 **사람 수에 상관없이 빠르고 정확한 추정이 가능**하다.

---

### 🧩 Tag Keyword

#PoseEstimation #PAF #2DPose #EnglishPaperStudy #NN방식학습 #논문정리 #piusAI
