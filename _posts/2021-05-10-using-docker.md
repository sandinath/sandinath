---
title: Using Docker
author: Sandipan Nath
date: 2021-05-10 11:33:00 +0800
categories: [Computer Science, DevOps]
tags: [containers]
math: true
mermaid: true
image:
---

(Last Updated: 05-10-21) Work in Progress: My experience so far working with Docker.

## Docker

---

<!-- # H1 - heading

<h2 data-toc-skip>H2 - heading</h2>

<h3 data-toc-skip>H3 - heading</h3>

## <h4>H4 - heading</h4> -->

Docker is a software tool for running applications in isolation on virtualized containers that can run on any computer. It can be a little confusing, so I will give a quick example. I used Docker to make this blog. This blog was made using Jekyll, a popular static site generator written in Ruby. Typically, you would have to install Ruby and Jekyll to your computer to get this website running, but I avoided that by using Docker containers. I pulled a Docker image for Jekyll from Docker Hub (more on this later) which had all the packages and dependencies (i.e., stuff) that I needed for the website. Doing this was much more lightweight and convenient than installing everything would have been. This also has the additional benefit of being able to run on any computer (that has Docker installed) without the hassle of downloading Ruby and Jekyll again. The cost of installing Docker doesn't seem much less than the benefits for this website in particular, but for other projects that use more software, the benefits can significantly outweigh the costs.