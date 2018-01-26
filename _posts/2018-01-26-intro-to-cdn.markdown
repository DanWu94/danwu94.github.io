---
layout: post
title:  "Introduction to Content Delivery Networks"
date:   2018-01-26 14:30:00 +0800
categories: book reading
---
This is the first time that I learn about the Content Delivery Networks(CDN).
The book I used is called Dissecting Content Delivery Networks, which is written in Chinese.
The book was published in 2012, so some of the notes below may be out of time.

Server Load Balancing(SLB) is one of the key technologies of CDN. Some of the SLB algorithms are:

Static:
1. (Weighted) Round Robin
2. (Weighted) Random
3. Source IP Hashing
4. Source IP and Source Port Hashing
5. Destination IP Hashing
6. UDP Packet Loading Hashing

Dynamic:
1. (Weighted) Least Connection
2. Least Response Time
