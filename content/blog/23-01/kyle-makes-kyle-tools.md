---
title: "Kyle Makes Kyle Tools"
tags: ['webmastery']
image: /blog/23-01/thumb.jpg
date: 2023-01-03T17:50:47-08:00
draft: false
---

My website is FINALLY up, wooooo!!! I worked on it for about a week and it's finally done... There are still a few tweaks I want to make, pages to add, but it should be working. I'll be improving the site's accessibility, too. :] Read on if you’re interested in how I made it! If not, see you in the next post?!?!

## Why make a website?

It's been a couple years since I've posted to social media. I miss having my own public space to dump stuff onto. I have a weebly site where I’ve archived drawings from the past couple of years, but it’s not ideal. It’s super easy to use, but I don’t have full control over it. My solution is to carve out my own little space on the web. Build a personal website!

I’ve tried to make one before, but I always give up about halfway through the process. My last attempt (shown below) is from 2020. At the time, I had NO IDEA what I was doing. All I had was super basic HTML/CSS knowledge (from messing with my tumblr theme back in the day) and a couple tutorials. I managed to make a gallery with a script I found, but I couldn't do much else. Everything was too much for my little brain to handle.

![Clicking through my 2020 website](/blog/23-01/web2.gif)

(I was really into Death Note at the time, and I wanted a place to put my fanart and videos LOL. funny cuz i didn't even draw much)

And here's a little bonus: I found an even older website I made when I was 15. It's super bright and FUGLY. I uploaded most of my images to imgur so they're gone. Forever!

![Clicking through the website I made when I was 15](/blog/23-01/web1.gif)

Fast forward to 2022, ready to give this thing another try... 

## Ok. How to make it???

DISCLAIMER: I'm just doing this for fun. I'm learning and I'm trying my best!!!

Like I mentioned earlier, I always give up at some point. The main obstacle has always been BUILDING it. I have a vision of what I want my website to look like, but I'm limited to my coding abilities. I want a gallery and a blog. This isn't impossible to make with pure HTML/CSS, but I imagine it would be really tedious to maintain in the long-run. When I update my site, I don't want to think about it too much. There haaaass to be a better way! So I decided to give static site generators a try. There are a ton of them. Here are a few I tried a while back:

- **Jekyll**: Couldn't even install it because of some problem with my ruby gems?? I fixed this (i think) recently, but I never went back to try it again. Oops!
- **Pelican**: I had just learned Python when I tried this so I thought it wouldn't be too hard to use but... I got frustrated at some point and quit. LOL
- **Zola**: Similar experience, hit an obstacle, got frustrated, quit.

After testing them and failing, I gave up on my website for a while. Fast forward (again) to December 2022, semester just ended, and I was itching to make my website again. I did some more research, looked into a few more generators, and gave myself two final options: Zonelets or Hugo!

From my (not very in-depth) research, [Zonelets](https://zonelets.net/) seems to be the easiest and quickest way to make a static blog. All you have to do is download the starter files and start editing them. The tutorials are really easy to follow. There's a lot of manual coding involved, but that's the fun of it. The script file is where all the magic happens so if you know Javascript, you can probably get it to do whatever you want. If I took the time to learn JS, I'd probably use this.

## Using Hugo

![Drawing of me dead on the floor](/blog/23-01/d1.png)

I ended up using [Hugo](https://gohugo.io/). It's definitely overcomplicated, but it works for me! If you watch a couple tutorials and read through the docs, it shouldn't be too difficult to make a website. I found it very helpful to read through the [Go template documentation](https://pkg.go.dev/text/template) as well as Hugo's [function reference](https://gohugo.io/functions/) Now, I COULD have started with a pre-made theme and messed with it to my liking. But I already had an idea of what I wanted so I ummmmmm.... made the process a lot more frustrating than it should have been. :P It was soooo satisfying to get it to work though. This was a good learning experience but now that I'm done I'm like....... WHY did I do it this way. 

Some helpful things:
- **Hugo related:**
	- [Theme from scratch (video)](https://youtu.be/aSd_Ha5nDkM)
	- [Generating an archive page (article)](https://www.thedroneely.com/posts/generating-archive-pages-with-hugo/)
	- [Pagination tutorial (video)](https://youtu.be/BSeYDNhTRB0)
- **CSS related:**
	- [Kevin Powell's channel](https://www.youtube.com/kevinpowell)
	- [Custom properties guide (aka variables)](https://css-tricks.com/a-complete-guide-to-custom-properties/)
	- And then I decided to learn [Sass](https://sass-lang.com/guide) and watched this [20 min intro](https://youtu.be/Zz6eOVaaelI). I'm not using it to it's full potential but it was neat. My css really needs to be cleaned up :X
- **Other:**
	- The gallery uses [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/)
	- I'm using a [sans-serif system font stack](https://systemfontstack.com/) :)
	- [ImageOptim](https://imageoptim.com/mac) to compress images (free for mac users only????)
	- [Cursor](https://gitlab.com/Enthymeme/hackneyed-x11-cursors)
	- [Neocities CLI](https://neocities.org/cli) - way better than dragging files, when I tried it for the first time it ignored nested folders? IDK


## Bye bye

PHEW that's all I want to say...for now. Thanks for reading! :)

![Drawing of me smiling](/blog/23-01/d2.png)
