---
layout: page
title: High Performance Computing, Distributed Sorting
gh-repo: lpratt30/lpratt30.github.io
---

In this competition, we selected and implemented an algorithm to do distributed sorting of data on a supercluster.  

We were graded based on how fast our code was relative to the rest of the class. My code outperformed 80% of the class. 

My performance came by meticulous memory management, careful algorithm selection, and use of ring topology to avoid network congestion. 

This was of course coded in C which is common in HPC. 

Unfortunately, I cannot share this code publicly as that could result in plagiarism for an ongoing course. 

However, I can share a small sample of the code, and note that I implemented sample sort (https://en.wikipedia.org/wiki/Samplesort): 

![Image](../assets/img/sample_code1.PNG)
