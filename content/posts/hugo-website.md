---
date: '2025-02-07T23:13:03+01:00'
draft: false
title: 'Setting up my website with Hugo'
aliases: ["/setting-up-hugo-website"]
categories: ["website design", "jamstack"]
tags: ["hugo", "design", "jamstack"]
author: Tomisin Olujinmi
cover:
  image: images/hugo-logo-wide.png
  caption: World's fastest static site generator
summary: Why I used Hugo to create my personal website
canonicalURL: https://tomisinolujinmi.com/posts/hugo-website
---

A personal  website is digital real estate. Having a domain name and hosting grants you your own tiny cranny of the Internet that you can completely lord over. Unlike a social media account, you can’t be de-platformed and you don’t really have to deal with people you don’t like. Everyone, I believe, should have at least a blog on their website. It is a plus if the website is self-hosted (although mine isn't).

[WordPress](https://www.wordpress.org) is the most popular option for people who want to build their own website and it is a great option. It is free, powerful, and quite customizable. However, it is overkill for most purposes. For my website, I decided to forego a traditional content management system like WordPress and opt for a static site generator instead.

A static website is easier and cheaper to host, offers a lot of granularity, and generally loads faster than a comparable dynamic website. Popular static site generators include Jekyll, Hugo, Eleventy, and Astro.

My first choice was [Jekyll](https://jekyllrb.com) but I couldn't find suitable documentation and it all seemed unwieldy. So, I decided to go with Hugo instead. Hugo is a static site generator written in the Go language. It is indisputably the fastest SSG on the market. 

Hugo requires three dependencies: Git, Go, and Sass. I have been spoiled by Windows operating system and I had to get used to working in the terminal. With some Googling, grit, and a little help from Perplexity, I started to get the hang of it. 

I installed the dependencies and by following the instructions in the Quickstart tutorial, I got my first static website up and running. Configuring the website involves changing the default settings in the hugo.toml (or yaml) file and adding new values. I added a theme, wrote some pages, and started putting this post together. 

I have learnt to use git commits to track changes and “back up” my website. I have also brushed my rusty HTML wrangling skills a bit. I understand the Jamstack appeal now.

The website isn’t complete yet as at the time of wrting but I am very happy with where it is currently and look forward to bringing my vision to life. 

If you'd like to learn more about Hugo and how it works, check out the [official website](https://gohugo.io/). [This book by Atishay Jain](https://www.manning.com/books/hugo-in-action/) has also been a lot of help :pink_heart:

