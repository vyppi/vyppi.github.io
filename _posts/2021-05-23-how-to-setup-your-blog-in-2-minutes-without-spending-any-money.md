---
layout: post
title: How to setup your Blog in 2 Minutes without spending any money
subtitle: Ever wondered how to setup your own tech blog?
tags: [jekyll, blog]
comments: true
---

I've been thinking about starting a Tech blog for quite some time now but was never able to pick a platform to use for blogging. My main concerns when choosing a platform where - 
* Time involved in setting up the Blog
* How Easy / Difficult it would be to write Posts / Mantain the Blog
* How and where to host the blog (_ideally for free_)

For the question on how to host the blog for free I figured that Github Pages would be a good candidate for hosting my blog.  
Given that I was going to use Github Pages, it meant that I would need to somehow bundle up everything into static files that could then be served from Github (which meant no DB really).  
After looking around for a bit I found out that there are Static Generator that will do this for you and the most prominent one that came across was jekyll. It was based on Ruby and seemed easy to setup but I was concerned about having to install ruby on my dev machine (and also the fact that I was least interested to learn a new language even the bare basics).  

### So Which Blogging Platform Finally?

Recently I stumbled across beautiful-jekyll which did not require me to setup anything on my dev machine and also sokved the purpose (gave me a set of static files that I could serve from Github). The only thing you need to know to run a blog powered by Beautiful-Jekyll is Markdown (Learn the basics [here](https://www.markdowntutorial.com/) in 5 minutes). 

### How to Setup my Blog on beautiful-jekyll>

Very Easy. Follow the below steps and you should be done in 2 Minutes. 

1. Register on Github
2. Login to your Github Account and go to [beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)
3. Click on Fork Button (top right)
4. After the Fork is complete you would see a repository with the name <your-user-name>/beautiful-jekyll
5. Click the Settings Button
6. Change the Repository Name to <your-user-name>.github.io
7. Naviagate to https://<your-user-name>.github.io
  
Thats it, your blog is setup now :)
