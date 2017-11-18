---
layout: post
title: "Pre-compiled CSS vs. regular CSS"
categories: css, scss, pre-compiling css
---

### Regular CSS
I'm going to start this post off by expressing my hatred for CSS. My experiences have almost exclusively been bad, no other language have made me want to rip my hair out nearly as much as CSS has.

I don't have a lot of experience working with CSS, and I'm sure some of the issues I have with it are bound to get easier as you learn more. However there are issues with CSS that I doubt will get solved - no matter how much you learn, such as limited means of organising your code and a syntax that makes it impossible to work by the golden rule of programming - "Do not repeat yourself.".

### Pre-compiled CSS
Pre-compiling your CSS do - I believe - solve a lot of these issues. The pre-processor syntax I've worked with is SCSS, however from my understanding most of the different options work to solve the same issues. SCSS adds things such as using variables, mixins, inheritence, and better syntax for nesting your code.

### This website
This website mostly gets its looks from a pre-built theme I've used with Jekyll. I've not changed too much in its CSS, but I've spent all the more time studying the CSS that came with the theme. I may or may not have shot myself in the foot a little bit with chosing the theme I did, as a lot of the presets are made in ways that are fairly hard for me to decipher.

I have modified some things though, and the SCSS feature I've probably made the most use of is variables. I've heard that variables actually do exist in newer versions of regular CSS, but it's not something I've ever previously used - although I dearly wish I had. 

I could have saved so much time in previous projects if I could have just changed a few variables to try out different color-schemes, instead of having to scroll up and down in an endless CSS file to hopefully find all the places where I need to change a value.

Speaking of endless CSS-files, I would never have been able to decipher any of the presets of this theme if it wasn't for imports. I'm a sucker for organisation, and the theme being divided into a bunch of different files has been key for me finding things. If it was all one long CSS-file, like what I've worked with before, I would probably have given up out of frustration a long time ago.

You can also see examples of nesting in the editing of the header, which in this case saved me from writing "#masthead" twice, but which in a big project would save a lot more.

## Pros and cons

So, above I mostly write about the good things about SCSS, so what can be the downsides? Well, one of the most obvious downsides is that it's yet another language to learn. It also requires more tools to actually turn it into something your browser can interpret, which means even more to learn. With regular CSS it's very simple to just open a text file and write.

Debugging SCSS code can also be an issue, as the generated CSS files don't match the code you've written. Thus an error on line x in your generated CSS can mean an error on a completely different line in your written SCSS file. This means we need to create source maps to properly debug our code - yet one more thing to learn.

CSS pre-processors is also a bit of a specialised knowledge. Every web developer knows basic CSS, not everyone knows a pre-processor syntax. If they do know one, it may not be the same as yours. This could cause problems in situations where you're working as a team, as it's hard to co-operate if you speak different languages.

My take away in regards to the benefits and downsides of CSS pre-processing is that it can be a very useful tool, but that you seriously should consider how much time it'll actually save you in comparsion to how much time you'll spend learning it.