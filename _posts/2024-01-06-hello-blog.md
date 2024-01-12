---
layout: post
title: hello, blog!
category: meta
date: "2024-01-12 11:40:35 -0500"
---

This post marks my first ever post on this blog! Here, I'll be talking about some of the reasons I started this blog, what I plan to do with it, and my hopes for what it will become. For the technically and detailedly inclined, there's also a section on how I made the blog, what choices I made along the way, and why I made them.

---
{: data-content="the why"}

The idea of writing a blog is a pretty new one to me. It's only been over the past 4 months or so that I've started to entertain the idea. I am not usually one to share a lot about myself with strangers - doubly so for strangers on the internet. I do believe that sharing your work with others is a fantastic way to progress, share milestones, and gain feedback; and so, with this blog, I hope to achieve my goal of sharing my work with more people. On top of that, I have a few other goals for this blog:
- create an archive of my work
- share my knowledge and experience with others
- give my friends, family, and peers a chance to see what I am working on
- find a creative outlet
- provide some external motivation to find & work on more projects that interest me enough to write about
- allow me to walk through my decisions more deliberately

With all that fantastic stuff I can work towards with a blog, I figured why not give it a shot!

---
{: data-content="the how"}

The path I took in making this blog hasn't been particularly straightforward, or efficient. Initially, my goal with this blog was as an exercise in full stack development, in which I would build a backend API (for serving blog posts, allowing me to post new blogs, and fetching media), a frontend website, and a hosting solution. After spending a day or two working on building a simple frontend, I decided (to put it kindly) that frontend development was not for me.

This process repeated a few times, each time with me raking in my expectations for what I would be able to add to the blog, and each time ending with the rediscovery of how little I enjoy working with CSS. Eventually, after this cycle had repeated enough, I took a step back and realized that my over-scoping of this project was keeping me from completing any portion of it. Not only that, but I wasn't working on the projects I actually enjoyed!

With this realization, I took some time and thought a little bit more about what I really needed out of a blog and what the minimum viable solution would be to get my blog posts out to the world. Some of the key criteria I was looking for was:
- no proprietary editor, I want to write my blogs in a plaintext, human-readable format (preferably markdown)
- easy publishing process
- customizable theming/content
- hackable

With all this in mind, I thought a bit more about some of the existing web technology available and realized that since I didn't need any interactivity, a statically served website would fit my bill quite well. And, if I was serving a static website, then I could host it on GitHub pages and save myself the trouble of having to host it myself! With a quick google search, I found that plenty of other people had come to a similar conclusion and were using GitHub pages in combination with [Jekyll](https://jekyllrb.com/).

In the end, I settled on using Jekyll in combination with GitHub pages, using GitHub actions to regenerate the website whenever I merge a new change (i.e., uploading a new blog post or changing some configuration). The website's theming is based off of [no-style-please](https://github.com/riggraz/no-style-please), in part so I can easily modify it, and in part due to my dislike of CSS. I use [Obsidian](https://obsidian.md/) as a markdown editor, as it allows me to preview my markdown & easily link between my posts.

---
{: data-content="the next"}

With an explanation of the technology I'm using in this blog and my thoughts about why I am blogging out of the way, I hope to begin a string of more technical articles about some of my projects. My goal is to focus on my decision making process, challenges I faced along the way, technical details, and my advice for any others working on similar projects. But, who knows! Maybe I'll continue adding a few personal notes to these blog posts - I've found writing about my thoughts to be more fun than I thought!

Thanks to everyone who read this post, and hopefully you'll stick around for the next one!