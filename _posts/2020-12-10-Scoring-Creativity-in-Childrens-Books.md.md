---
layout: post
title: Scoring Creativity in Childrens Book Covers
subtitle: Method combines computer vision and network centrality algorithms to rate artwork
comments: false
---

I set out to find a quantative approach to assessing visual creativity. Within their [2015 paper](https://arxiv.org/pdf/1506.00711v1.pdf) Elgammal and Saleh  describe a general formula for assessing creativity for art of any kind, and then apply it to an archive of 62,000 significant western paintings. This approach defines the creativeness of a particular work as a combination of its originality and how influential that work has been. With this definition, the creativity of a specific work of art can be assessed by quantifying how dissimilar it is from the works that preceded it and how similar it is to subsequent works using computer vision. 
I chose to implement this technique and apply it to the cover art of children's books, because I find them particularly creative and enchanting.

My paper can be found [here](https://github.com/agudiswitz/Anton-Gudiswitz/blob/master/assets/Gudiswitz_CreativityinChildrensBooks.pdf)

![Results from the experiment](https://github.com/agudiswitz/Anton-Gudiswitz/blob/master/assets/img/ChildrensBookScoresGraph.jpg)

