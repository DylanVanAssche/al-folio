---
layout: post
title:  A fresh new website
date:   2020-04-11 12:00:00
description: My new personal website is online!
---

### My old portfolio website

<div class="col three caption">
    <img class="col three" src="{{ site.baseurl }}/assets/img/old-portfolio-website.png">
    A screenshot of my old portfolio website with my projects, thesis and how to contact me.
</div>


Over the last couple of years, I ran my own personal portfolio website.
My portfolio website was very useful during these years to show off my skills and projects I was working on.

Besides my projects, it was also a good way to put yourself out there.
It provided me some visibility on the Web and a way for recruiters to access my CV directly.
Recruiters could just download my CV and see how I might fit the profile they were looking for.

However, since I started a PhD at [IDLab Ghent](https://idlab.technology), I needed a space to list my publications and talk about my research.
I had two options, either extend my website or build a fresh one. 
I went for the second option since I wanted to update the technology stack behind my website anyway.

### Time for something new!

For the past few months, I have been looking into the personal websites of my colleagues to see which technologies were used by them.

Most of them are using [Jekyll](https://jekyllrb.com/) to build their websites.
You can write your content in [Markdown](https://en.wikipedia.org/wiki/Markdown) and converted by Jekyll into HTML pages.
Markdown is easy to write and makes it much easier to create content for your website. 
Since Markdown is text-based, you can write it in my favourite text editor: [Vim](https://www.vim.org) :smiley:
If Markdown is insufficient, you can always embed HTML tags into your Markdown file without any issues.

{% highlight mkd %} 
# Hello World

You can use Markdown to write content for your Jekyll website!
{% endhighlight %} 

Jekyll also supports [Liquid templates](https://jekyllrb.com/docs/liquid) in your pages.
These templates are processed when building your website by Jekyll.
Since I'm researching Semantic Web technologies, I want to add Linked Data to my website.
I am going to use Liquid templates to create [JSON-LD](https://json-ld.org) snippets to add machine readable information to my website.
This way, the information you're reading right now, can also be read and understood by machines.
I will write another blog post later on about this, keep an eye on this blog :wink:.

My new portfolio website has dedicated [blog section]({{ site.baseurl }}/blog) where I will blog about my research, my life and even the universe.
Besides the blog section, I also have a place to list my research [publications]({{ site.baseurl }}/publications).
The list is now almost empty, but I'm sure that the list will grow over time :sunglasses:.
