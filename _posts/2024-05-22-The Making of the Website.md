---
title: The Making of the Website
date: 2024-05-22 12:52:07 +0100
categories: [Projects]
tags: [Website, Networking]     # TAG names should always be lowercase
description: The story behind the website and the technical decisions involved in its creation
---

# Introduction

In this post I will be sharing my journey and thought process in making this website.

previosuly i dont have a good place to share all of these. I tried with linked in with this post (link) but present with two major problems. Limited customisability of each and not suitable to display code and the second is that the throught my writing, i always have a conflict of how detailed and the audience of my article. I could make it simple and easy to understand but that would mean. So with this website, i am aiming for a more deatiled posts and with a more technical audience. 

moving forward this will be the place that i will yap about my projects and discoveries


# Motivation:

My main motivation in making this is the fact that a lot of my projects are left and forgotten. Things that i thought i will remember for a long time i will literally forgot

I dont give enough credit cause sometimes when i look back i dont remember much on what i did especially for small one off weekend project. For

I learnt a lot but i dont document them so sometimes i just forget 

Not only that, even for long term projects i tend to forget the struggle and the effort i put into it

for example, the embedded systems project, i remembered there were so much interesting stuff that i thought i wouldnt forget but now few months passed and i already forgot a lot of the details. Sure I

I believe this is an important part of engineering

sometimes i revisit a project and end up looking at google with a bunch of purple links (which means i have googled them before) but i ended up needing to re-do the things i shouldve discovered

things like design justification, why i choose this specific approach and things like that are the kinds of i most often forget about

not only that, i believe that techincla communication is important for engineers as i belive that your idea is only good only if you can explain them especially when working with other engineers so with this i
will try my best to improve my technical explanation skill. I appreciate and love a good well written explanation of something complex, so i would like to have such writing skills


# Requirements

Before starting, i have to set some some requirements for my website because it is very easy to try to achieve too much and not even complete which i have learnt my lesson many times but still keep repeating.

1. **Just Works (Reliable)**  
I want something that just works. Although i have learned a bit about web development in the past, using a web framework and designing my own website would just take too much time and takes

4. **Easy to post**  
In addition to just works, I want to use it long term, so it has to be easy to create post and customise. writing custom html file for each post is really not practical. I dont mind not having full customisability as long as the options that i have is enough - somehing like a markdown file for each post but with some extra options will be perfect

2. **Free**  
Why not? With the idea of creating and hosting your own website, there are a lot of free and open source options, or make it from scratch where there are a lot of tutorials online. I think the payoff of using a paid website creator such as Wix is just not worth it for a personal blog website.

4. **Good Readability and UI**
Designing my own ui and graphic design might seem tempting due to its flexibility on customisability but as I have discovered early i am not talented for graphic design and ui design would not be the same and it will take a lot of time to make it what i consider as acceptable. So, a website template seem good




# Implementation

## Initial Considerations

My experience in web development are quite limited so some of these might be wrong

Although having some experience creating a bare bones website in my previous cs50x course i took last year, the knowledge is pretty limited and pretty limited on the design and UI elements of the website. Making the website look pretty and readable will take a lot of effort and time.

Using a well known web framework to build the website seems the most middle solution balance of flexibitly and time but there are too much options for this and im not planning to go down the rabbit hole of web dev but still you would still likely need to desing the front end which i am not keen to do atleast for now


## Github Pages

After looking for options online there is an option of using github pages to host my website and suprisingly there are a lot of templates that are free to use.

Github allows users to host their own websites on your repos for free. It turns out it is actually a common way for web developers to have thier website as a repo, build and run locally and when its ready, it will be pushed to the online repo and automatically built and launched.

Even with other services such as netlify and cloudflare pages, you can just link your repo and have set how the commands to build the website, and bam it will automically host the website. 

Github does specify a 1gb max file size and 100gb bandwith limit [source](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#usage-limits). I am pretty sure i will not reach that limit but it will be interesting to see the traffic of the website perhaps it would probably a topic for another project.


## Jekyll and Ruby

There are a lot of templates to choose from, but since i am planning to just make a static web page and not a web app, the templates i want to use is Jekyll which is written in Ruby.

Jekyll is a static site generator which uses a markdown file to generate each page which is perfect for my purposes. Markdown format is easy to write and customise. The tradeoff between customisability and ease fo use is justified for markdown in my opinion


## Chirpy Template

There are a lot of templates on Jekyll templates on [Github](https://github.com/topics/jekyll-theme) to choose from. But i have chosen chirpy template which has a starter template that you can easily directly use and sets up everything for you with minimal configurations.

By using the starter template, customising few variables in the `_config.yml`, and enabling github pages deployment, the webstie is ready to be access across the world. The guide for this is shown here [guide](https://chirpy.cotes.page/posts/getting-started/)

I was suprised how easy it is to host this beautiful website and let me remind you that it is FREE!

A lot of customisation can be made except for the general theme which is fine as is but can be seen as limiting especially since a lot of people are using this theme.

I even enabled comment section for each post using giscus which is supported by Chirpy

Honestly i wonder how the internet would be without the open source and i am forever grateful to all the contributors to open source projects and one day I wish I can. Obviously in this case all credit to the creator of this template.


## Custom Domain

To implement a custom domain for my website, there are a lot of outdated guides online and 



## Future Improvements

As said the theme allows for customisation for some elemets of but it lacks customisability on but it is uderstandable as it is a tradeoff for ease of use. Things like fonts, text formatting are pretty limited so in the future I might migrate to another theme minimal mistakes as it allows for more custmoisabiility but requires more configuration. So i am not going to migrate to that but maybe in the future



# Credits and reverse footnotes

[Chirpy github pages template](https://github.com/cotes2020/jekyll-theme-chirpy)

[Website Favicon Created By Good Ware](https://www.flaticon.com/free-icons/circuit)

