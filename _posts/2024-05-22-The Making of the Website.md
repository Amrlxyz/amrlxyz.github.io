---
title: The Making of the Website
date: 2024-05-22 12:52:07 +0100
categories: [Projects]
tags: [Website, Networking]     # TAG names should always be lowercase
description: The story behind the website and the technical decisions involved in its creation.
---

# Introduction

In this post, I will share my journey and thought process in making this website.

Previously, I didn’t have a good place to share all of these. I tried LinkedIn with this post[^linkedin-original-post] but faced two big problems. 

The first was the limited customizability and not being suitable to display code.

The second was that throughout my writing, I always had a conflict about how detailed to make it and who the audience is. I could make it simple and easy to understand, but that would mean losing some details.  

With this website, I aim for more detailed posts for a more technical audience. Moving forward, this will be the place where I will yap about my projects and discoveries.

# Motivation

My main motivation in making this is the fact that a lot of my projects are left and forgotten. Things that I thought I would remember for a long time, I literally forgot.  

I don’t give enough credit to my work because when I look back, I don’t remember much of what I did, especially for small one-off weekend projects.  

I learned a lot but didn’t document them, so sometimes I just forget. Even for long-term projects, I tend to forget the struggles and effort I put into them.  

For example, the embedded systems project. I remember there was so much interesting stuff that I thought I wouldn’t forget, but now a few months have passed, and I already forgot a lot of the details.  

Sometimes I revisit a project and end up Googling the same things again, seeing a bunch of purple links (which means I’ve Googled them before). I still need to redo things I already discovered.  

Things like design justification, why I chose a specific approach, and other details are the ones I most often forget.  

I believe this is an important part of engineering.  

Not only that, but I believe technical communication is important for engineers. Your idea is only good if you can explain it, especially when working with other engineers. So with this, I will try my best to improve my technical explanation skills.  

I love and appreciate a well-written explanation of something complex, and I would like to have that kind of skill.

# Requirements

Before starting, I had to set some requirements for my website. It is very easy to try to achieve too much and not even finish, which I have learned many times but still keep repeating.  

1. **Just Works (Reliable)**  
   I want something that just works. Even though I learned some web development in the past, using a web framework and designing my own website would take too much time and effort.  

2. **Free**  
   Why not? There are a lot of free and open-source options, or you can make it from scratch with tutorials online. I think paid website creators like Wix are not worth it for a personal blog.  

3. **Easy to Post**  
   I want to use it long-term, so it has to be easy to create posts and customize. Writing a custom HTML file for each post is not practical. Something like markdown files with extra options is perfect.  

4. **Good Readability and UI**  
   Designing my own UI and graphics is tempting because of the flexibility, but I’m not good at graphic design. It would take too much time to make something acceptable. Using a website template seems like a better option.  

# Implementation

## Initial Considerations

My experience in web development is quite limited, so some of this might be wrong.  

Although I made a simple website during my CS50x course last year, my knowledge of design and UI is pretty limited. Making the website look good and readable would take a lot of effort and time.  

Using a well-known web framework seemed like the best balance between flexibility and time, but there are too many options, and I didn’t want to go down the web dev rabbit hole. Also, most frameworks still need some front-end design, which I didn’t want to do right now.  

## GitHub Pages

After looking online, I found GitHub Pages as an option to host my website. Surprisingly, there are many free templates to use.  

GitHub allows users to host websites on their repos for free. It turns out it’s a common way for web developers to have a repo for their website, build and run it locally, and push it online when ready.  

With other services like Netlify and Cloudflare Pages, you can just link your repo, set up build commands, and it will automatically host the website.  

GitHub Pages has a 1GB max file size and 100GB bandwidth limit[^github-pages-limits]. I’m pretty sure I won’t hit that limit, but it will be interesting to see the website traffic. Maybe that could be another project.  

## Jekyll and Ruby

There are many templates to choose from, but since I just want a static page and not a web app, I chose Jekyll, which is written in Ruby.  

Jekyll is a static site generator that uses markdown files to make pages, which is perfect for my purpose. Markdown is easy to write and customize, and I think it’s a good balance between customizability and ease of use.  

## Chirpy Template

There are many Jekyll templates on GitHub[^jekyll-themes], but I chose the Chirpy template. It has a starter template that sets up everything with minimal configuration.  

By using the starter template, customizing some variables in `_config.yml`, and enabling GitHub Pages deployment, the website was ready to go live.  

The Chirpy template allows some customization but not for the general theme. That’s fine for now, but some might find it limiting since many people use this theme.  

I also enabled a comment section for each post using Giscus, which Chirpy supports.  

Honestly, I’m amazed by open-source projects. I am forever grateful to all contributors, and one day I hope I can give back too.  

## Custom Domain

To add a custom domain, I found a lot of outdated guides online. I might document this process separately.  

## Future Improvements

As mentioned, the theme allows customization of some elements but lacks flexibility in things like fonts and text formatting. In the future, I might switch to a more customizable theme like Minimal Mistakes, but it requires more configuration.  

# Credits and Footnotes

- [Chirpy GitHub Pages Template][chirpy-github-repo]  
- [Website Favicon Created By Good Ware][circuit-favicon]  

[^linkedin-original-post]: LinkedIn - [Original Post Example](https://www.linkedin.com)  
[^github-pages-limits]: GitHub Pages Usage Limits - [Source](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#usage-limits)  
[^jekyll-themes]: Jekyll Themes on GitHub - [Explore Here](https://github.com/topics/jekyll-theme)  
[^chirpy-github-repo]: Chirpy GitHub Repository - [View Repository](https://github.com/cotes2020/jekyll-theme-chirpy)  
[^circuit-favicon]: Circuit Favicon by Good Ware - [View Icon](https://www.flaticon.com/free-icons/circuit)  
