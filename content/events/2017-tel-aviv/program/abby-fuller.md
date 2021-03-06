+++
Talk_date = ""
Talk_start_time = ""
Talk_end_time = ""
Title = "Creating effective container images "
Type = "talk"
Speakers = ["abby-fuller"]
+++

Sick of getting paged at 2am and wondering “where did all my disk space go?” This has actually happened to me, and you can learn from my mistakes! New Docker users often start with a stock image in order to get up and running quickly, but that isn’t always the right answer. Creating efficient images is often overlooked, but important. Beyond saving resources, using minimal images also delivers important security benefits: include only what you need and not a whole runtime that might have security vulnerabilities. In this session, I’ll talk about how to create effective images and lessons I’ve learned from running containers in production at a number of startups. I’ll also cover topics like “how do layers work?” and some things you should think about when creating your images, such as; choosing or creating the right base image; the importance of caching; using RUN statements conservatively; cleaning up as you go. I’ll also address best practices; both at a high level with multi-stage builds; and some language-specific best practices, for example, tips and tricks for creating containers for Node.js vs Go. To illustrate these points, we’ll cover: How layers work?, Choosing a base image vs. creating your own, The basics of building minimal images and the importance of choosing a base image vs. creating your own, The importance of caching, High level best practices for Linux containers (in general, and some language specific examples), High level best practices for Windows container images, New and improved: multi-stage builds, Good vs. not so good Dockerfile examples, Docker Image Scanning, and other friends, and looking to the future for more optimization.
