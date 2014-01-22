---
layout: post
title: "Blogging with Jekyll/Octopress"
date: 2013-12-16 11:19:16 -0500
comments: true
categories: [Blog, Blogging, Jekyll, Octopress, Ruby, Developer]
---

As I have recently graduated from University of Toronto, finished [Bitmaker Labs](www.bitmakerlabs.com), a Toronto based intensive coding school, and will be starting a new job as a Software Developer in the new year, I figured it was a good time to launch a blog to keep track of and be able to share the knowledge I acquire along the way.

<!--more-->

I was originally going to launch a blog using [Wordpress.org](https://wordpress.org). I thought it would be a good excuse to expose myself to some PHP over time. I spent a couple of days playing around with the PHP source code, trying to get things to work the way I wanted them to, but then decided to look for other "quick deployment" solutions. 

I am a little bit stubborn in that I like to do everything on my own and build things from scratch (i.e not make use of all the available Wordpress plugins that will do everything for you). Although this is a great way to get a deep understanding of the tools and technologies you are using (really a great way to learn for yourself), it is definitely NOT the most time efficient way of getting things done and as stubborn as I am, I am realizing more and more how important it is to pick and choose what pre-existing tools you should make use of.

Anyways, after deciding I was spending too much time when I had so little, I thought it might be a good idea to build a personal blog from scratch in rails, until I stumbled upon [Jekyll](http://jekyllrb.com/) and [Octopress](http://octopress.org/). Jekyll is "a simple, blog aware, static site generator" bundled as a ruby gem. Jekyll doesn't come with any templating, CSS, HTML or styling elements, it is pretty "bare bones", so to get a blog up and running really quickly with some element of design taken care of, you can use [Octopress](http://octopress.org/), a framework written for Jekyll. 

Octopress calls itself _**"A blogging framework for hackers"**_. It provides an HTML5 template and a mobile first responsive layout. If you are already a Ruby developer and use Git the setup is very quick and the [getting started documentation](http://octopress.org/docs/) is straightforward. The nice thing about Octopress is it is very lightweight and flexible, you can choose to use a pre-existing theme (of which some good 3rd party themes can be found [here](https://github.com/imathis/octopress/wiki/3rd-Party-Octopress-Themes)), and it is easy to customize and edit source code as much or as little as you want.

Another reason I am liking the Octopress solution over Wordpress, is it avoids the need to add posts and pages through a graphical admin page. With Octopress everytime you want to add a new post just run the command `rake new_post["title"]` and start typing your post in your favorite text editor ([Sublime](http://www.sublimetext.com/) in my case!) in markdown format.

You can also easily deploy your Octopress blog to Github or Heroku, and again [the documentation](http://octopress.org/docs/deploying/) is quick and straightforward.

I got everything up and running and configured within a couple of hours, and am having fun playing around with the customization of the site. Styling templates are provided as [SASS](http://sass-lang.com/) files, so for someone who hasn't ventured outside of basic CSS much, it is fun to play around with these _**Syntactically Awesome Style Sheets**_.
 
Happy blogging everyone! 
