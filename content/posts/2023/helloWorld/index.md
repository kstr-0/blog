---
title: "Hello World"
date: 2023-03-21T23:42:41Z
draft: false
---

### Is this thing on?
I'm gradually starting to become more and more disenchanted with social media. Whilst I still do keep around some old accounts here and there, I am very seldomly using social media for its intended purposes and despite social media playing a large role in our society today, I am starting to feel that the cons outweigh the pros. So, I thought it'd be a good idea to finally get my blog up and running. Comfy right?

### Getting started (again) 
Admittedly, this isn't really my first blog. This time I'm using [Hugo](https://gohugo.io), a fast and flexible static site generator written in Go language. I wanted to move away from what I had previously been using ([Ghost](https://ghost.org)) and have my blog sit in a git repo in plain text instead. When I push any changes to the blog's [GitHub repo](https://github.com/kstr-0/blog) an active runner will automatically build this website. The little magical elves inside the Github datacenters set up an ephemeral Linux environment that will clone my repository, generate the static website and then deploy it to my webserver. The whole action only takes around 25 seconds and the SSH key and other sensitive data are stored in the environment's secrets, so I don't have to worry about having to copy them between the different machines I own.

I'm aiming to write posts that will mainly centre around technology however I may write about my other interests too. It's my blog after all!
