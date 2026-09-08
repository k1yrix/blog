---
title: "I migrated my website design (part 2: the blog)"
date: 2026-09-07 21:45 -0400
# last_modified_at: 2026-09-07 19:30 -0400
categories: [blogs, website updates]
tags: [website, updates, design]
pin: true
description: I overhauled my blog. again.
---

so I changed stuff up again. how fun.

you're probably wondering "why again?"

## why change it up again?
this was just some random thing that was just brought up overnight. I don't remember how exactly, but I found someone was using jekyll with the chirpy theme. I digged deeper and thought "that looked cool. maybe this will actually fit for my blog site."

how this is rigged up is that it reads markdowns from a specifc directory and sets up the formatting into static html. you can also assign attributes to your posts to categorize it efficently. (yes I get to use markdowns again for the first time since v1. that's so cool am I right) and that's really it. getting back to markdowns with good website design was basically the main factor of migrating the blog site to jekyll. 

and I somehow got it finished over the course of just a couple of hours on the night of september 6th. I was surprised I was able to get this done and over with quickly.

## what kind of progress you made?
check it out here: <https://github.com/k1yrix/blog-v3-dev>

I want to do it on a private repo so I can test deployments without having to deploy on the main repo. (I could have done branches so you guys could've tracked what I was doing publicly and I could've done a direct pull from there, but eh whatever)

a lot of it was basically setting up the config, laying out the css, and migrating all the posts over. (while also pointing things to the correct place)

the css part took me a lot of time because I had to inspect element the page to figure out what css element controls what attribute. if you take a look at [the css overlay file](https://github.com/k1yrix/blog/blob/main/assets/css/jekyll-theme-chirpy.scss) for this blog site, including its [commit history](https://github.com/k1yrix/blog-v3-dev/commits/main/assets/css/jekyll-theme-chirpy.scss) for this file, you can basically see that I had roughly 10 additional variables I had to find and layer on top of the regular variable changes to the root of the css here. this is on top of having to find the variable on a literal flat structure on the main css and having to use a css cleaner for it.

## wait there's comments now???
yep. apparently with chripy, you can embed comments in the form of a github discussion post on this repo. all it basically takes is to just add [giscus](https://giscus.app/) to this repo and set the configs. so now you have a reason to yell at me if you want to say something, and assuming I set this up right, you can drop your thoughts in the bottom of this post after you read all this!

you can even react to this post 😮 (yeah I know shocking /s)

---

anyways, there you have it. a proper blog website ig. that's all I have to say really. 