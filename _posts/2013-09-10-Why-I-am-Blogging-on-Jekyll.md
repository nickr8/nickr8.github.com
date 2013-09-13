---
layout: post
title: Why I am Blogging on Jekyll
date: 2013-09-10
---
I used to use a service called [scriptogr.am](http://scriptogr.am) (about a week ago) as a CMS for my blog. The service was very simple: you put your posts in the markdown file format into a specific folder on your dropbox. Then scriptogr.am generated the blog automatically. 

It is a very good solution for people who want to have a free blog up and running in no time. It is even possible to change the look and feel by modifying a css file. 

What it lacks is *total* control and *insight*. Even though you can change bits and pieces it is still largely a mysterious black box. For the same reason I also abandoned [Wordpress](http://wordpress.org) as a blogging platform. I  want to *understand* what is going on behind the scene. 

This mentality reveals the geek in me. Most people are happy if something works, works well and looks good. Then there are the people who want to know *how* it works and *why*. These people are the geeks, the engineers and tinkerers.

So, what is Jekyll?

Well, Jekyll is a lightweight static site generator. This means that the html file is not generated new every time the page is served. Also, the content is separate from the structure of the site. This means that there is a folder in which my posts are in plain text format (in Markdown to be exact). Every time I add a new post I have to make a new "build" which converts the markdown files into html which is static. 

The benefit of a static site is that it is not only that it is easier to understand the inner-workings compared to CMS like Wordpress but it is also a lot faster and more secure. Additionally, because the site is static it can be hosted with some free hosts, like [GitHub](http://github.com) (I am currently doing this). 

Although I am now starting to understand how a blog really works from the inside and have total control over it, there are some downsides. 

The one that comes to mind immediately is that it is more time consuming. Every time I want to publish a post I have to "build" a new site and then push it to GitHub. Also, the look is butt-ugly in the beginning without any customization. This will change as I am going to start styling the site in the coming weeks.

If you want to have total control over your blog or site and are interested in web development I highly suggest you try out [Jekyll](http://jekyllrb.com).