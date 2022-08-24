---
toc: true
layout: post
description: Lauching my new AWS Lambda/Huggingface Optimization Project
categories: [markdown]
title: Launching the Serverless Optimization Project
---
# First Post about this project

After about a month of setting up basic concept and executing it, I have reached a milestone and am ready to start sharing my results and plans regarding this project.

Essentially, my goal was to run a fairly extensive optimization test with the goal of running Huggingface language models on AWS Lambda Serverless.

The idea is that hosting these large, relatively slow language models can become expensive on dedicated and GPU equipped dedicated hosts.

If it were possible to make use of the AWS Lambda Serverless environment and utilize all available hardware and optimization tools and techniques, would it be possible to obtain acceptable response time?

This is what I wanted to find out!

After some initial research, I discovered that there are two kinds of CPU architectures available on AWS Lambda:

There is the X86 processor and also the Graviton2 ARM architecture.

According to Amazon, there is a lot of potential power and price savings to be had with this processor.

So, I set out to set up a Optimization Test where I could get response times from a basic Huggingface language model for 2 different architectures and 4 different operating systems.

They are:

* X86 (X86_64)
* ARM (aarch64)

and 

* Amazon Linux 2
* Amazon Linux 2022
* Ubuntu 20.04
* Ubuntu 22.04

<iframe title="ServerlessTimings - Small - Page 1" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMzYwZDM5OWEtMGE0OC00YTBkLTg3M2QtYTZiNDMwZWQ0YmIwIiwidCI6ImZiMzMyOTk2LTQ3NjktNGJlNi05ZjA0LWZmNDgwM2Y3ZmFmOCIsImMiOjF9" frameborder="0" allowFullScreen="true"></iframe>