---
layout: post
title: "Static Site Generators"
categories: web-development
---

## What is an SSG?
A static site generator is a tool which allows you to (fairly) easily create good-looking websites with high performance. The SSG takes a sites source files, in the form of templates and text, and outputs a static html site.

Static sites have a lot of benefits, such as performance and sequrity. Accessing a static site is generally very fast, and a static site can handle a lot of traffic without any problems. Since the site is just what its name says, static, this also means that sequrity breaches are very unlikely. If you can't change anything in the site, it's hard to cause mischeif.

A static site also means a built in back-up. Since the actual site is generated from the sites source-fils, there's no risk of data-loss from server problems. At least assuming you store your source files in a decent place.

## My experience

To create this website I've been working with Jekyll, and that's been a good experience. Apart from trying to get docker to run (and then ending up on linux anyway, making that whole ordeal redundant) I've had little to no problems. 

I still can't say I've enjoyed creating this website - the more I try out web development, the happier I am that I chose UDM and not WP. However, at least with using Jekyll the fruit of my frustration is a website that looks fairly decent - instead of like a flashback to the 90's.

If I were to have a reason to create a webpage in the future, I would definitely be using an SSG. 

## When (not) to use SSGs

SSGs may be great, but that does not mean they're suitable to use for all types of projects. With a static site comes limitations, and while these limitations at times are what makes SSGs good, they can mean you can't do what you need to do.

Since a static site does not in any way use a database, anything requiring users to log in can't be handled by an SSG. Some things that would require a user to log in can still be implemented in a static site by outsourcing the log in, such as using Disqus to allow users to comment on posts. However, for some projects you just need a database, and then you can't use a static site.

Other things that can cause problems with an SSG is if you have a site that's edited by multiple people. With a blog you could have multiple authors, as each author would simply create a new text-file for each post, but if you have several developers making more invasive changes to a sites design you could end up with problems. It can be solved, as long as you make sure you don't try to edit the files at the same time, but to me it feels like a recipie for ending up with incompatible source files, and accidentaly erasing another persons work.

For a lot of projects SSG's are perfect though. Blogs are an obvious example, but also for various types of promotional websites, course platforms, online portfolios, educative websites, et.c. Basically - anything that does not require a database. I could even see myself using an SSG to create a sort of personal wiki-page of notes from different lectures, or as an overview of different craft projects - even though I'd never upload that online.


