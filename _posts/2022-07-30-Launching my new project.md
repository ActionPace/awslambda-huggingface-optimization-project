---
toc: true
layout: post
description: Lauching my new AWS Lambda/Huggingface Optimization Project
categories: [NLP]
title: Launching the Serverless Optimization Project
---
# Natural Language Processing for Everybody

After about a month of setting up basic concept and executing it, I have reached a milestone and am ready to start sharing my results and plans regarding this project.

Essentially, my goal was to run a fairly extensive optimization test with the goal of running Huggingface language models on AWS Lambda Serverless.

The idea is that hosting these large, relatively slow language models can become expensive on dedicated and GPU equipped dedicated hosts.

If it were possible to make use of the AWS Lambda Serverless environment and utilize all available hardware and optimization tools and techniques, would it be possible to obtain acceptable response time?

![PowerBI1](https://github.com/ActionPace/awslambda-huggingface-optimization-project/raw/master/images/PowerBI1.png)

This is what I wanted to find out!

After some initial research, I discovered that there are two kinds of CPU architectures available on AWS Lambda:

There is the X86 processor and also the Graviton2 ARM architecture.

According to Amazon, there is a lot of potential power and price savings to be had with this processor.

So, I set out to set up a Optimization Test where I could get response times from a basic Huggingface language model for 2 different architectures and 4 different operating systems.

![Google pic1](https://github.com/ActionPace/awslambda-huggingface-optimization-project/raw/master/images/ProcessorsAndOS.png)

<hr style="height:1px;border:none;color:#333;background-color:#333;" />

| <strong>[Understand In Depth](https://actionpace.github.io/awslambda-huggingface-optimization-project/understand)</strong>|<strong>[Optimize Effectively](https://actionpace.github.io/awslambda-huggingface-optimization-project/performance)</strong>|<strong>[Deploy AI Models](https://actionpace.github.io/awslambda-huggingface-optimization-project/deploy)</strong>|<strong>[Build Applications](https://actionpace.github.io/awslambda-huggingface-optimization-project/appdev)</strong>|
| :-: | :-: | :-: | :-: | 
| ![Google pic1](https://github.com/ActionPace/awslambda-huggingface-optimization-project/raw/master/images/Icon4.png)|![Google pic1](https://github.com/ActionPace/awslambda-huggingface-optimization-project/raw/master/images/Icon3.png)|![Google pic1](https://github.com/ActionPace/awslambda-huggingface-optimization-project/raw/master/images/Icon2.png)|![Google pic1](https://github.com/ActionPace/awslambda-huggingface-optimization-project/raw/master/images/icon1.png)|
