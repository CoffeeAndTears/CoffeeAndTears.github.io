---
layout: post
title: Hosting your blog with Sandra.Snow and Github Pages
author: Erik
category: blogging
series: 
	name: Kickstarting your blog
	current: 1
	part: Hosting your blog with Sandra.Snow and Github Pages
	part: Adding Disqus for reader interaction
	part: Embedding code snippets with Gist
---

So, you want to set up a blog. Good for you! Maybe you want to create an online persona for yourself, or maybe you just want some place to record your thoughts. One way or the other, it will be a lot of work to maintain, but it will also help you tremendously in organizing your thoughts and proper writing. The last thing you'll want to be bothered with is maintaining the technology which powers your little corner of the internet! 
<!--excerpt-->

##Sandra.Snow to the rescue
Enter: [Sandra.Snow][1]. I could write my own bit of prose to explain what exactly Sandra.Snow is, but the guys who maintain the project have already done that for me:
    
> Sandra.Snow is a Jekyll inspired static site generation tool that can be run locally, as a CAAS(Compiler as a Service) or setup with Azure to build your site when your repository changes. It is built on top of [NancyFX][2]. 

So what does this mean in practice, to you, the soon-to-be-owner of a new blog? In practice, you will have a few template files which define the look and feel of your pages, and a (hopefully) growing amount of text files using the [Markdown format][3]. These text files are the bread and butter of your blog: the articles. To update your blog you would write a new article in this Markdown format and then use Sandra.Snow to generate HTML pages out of your content. When that's done, you push it to your website. This could be any place, but the fanciest way is to push it to GitHub.

[1]: https://github.com/Sandra/Sandra.Snow
[2]: https://github.com/NancyFx/Nancy
[3]: http://en.wikipedia.org/wiki/Markdown
