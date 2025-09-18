---
layout: post
title:  "Am I doing it wrong?!?!"
tag: blog, tech, development
#category: general
---

# Old man yells at cloud

![Old man yells at cloud](/assets/old-man-yells-at-cloud.jpg)
Pun intended

Sometimes I feel like I am just getting too old to keep up with the kids these days, with their new fangled technology. Back in my day it was all static HTML, there was no "React", there was now "WEB2" never mind WEB3! And there was no AJAX yet.

But here I am, building out this blog and website using [Jekyll](https://jekyllrb.com/). It generates static HTML for the website, built out from templates and Markdown. Lovely jubbily.

But this is the part I don't really "get", which is why it runs as a daemon, sure it's nice that it serves up the files immediately when developing. But a lot of the documentaion I read is people putting a reverse proxy, pointing at the daemon. Which just seems to defeat the whole point of it? No?

At the moment, I'm having Jekyll generate the files, and I'm pushing those to [Git](https://github.com/d-j-h/blog) so that the world can see my diabolical Markdown, and even worse commit messages. (I never seem to remember that branches exist!). And then my web server, in this case nginx (I <3 nginx), just points at the static HTML and et-viola. A VERY limited attack surface, as it's entirely HTTP, rather than some middle-ware!

Am I just being dumb?

/Rant
