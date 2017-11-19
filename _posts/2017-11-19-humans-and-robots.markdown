---
layout: post
title: "Humans and robots"
categories: web-development
---
## Robots.txt
The internet is filled with robots. Some of them good, some of them malicious. To be able to optimise the web for the good robots, such as the ones that index webpages for search engines, we use a standardised file called "robots.txt". Robots.txt acts as a guide to what webpages should be accessed by non-human agents. Thus, if you have pages on your site that would not benefit from being indexed or searchable, you can disallow robots from visiting them in your robots.txt-file.

The robots.txt-file is however as described above just a guide, not a law. The only reason it works is that the people who have built the robots have trained them to look for a robot.txt-file, and to obey the instructions in it. As it's an agreed upon standard, most robots with good intentions are coded in this way - but the file does not provide any security against malicious robots, for example bots trolling for email adresses. Since the creators behind those bots do not have good intentions, they also have no reason to make their robots obey the robots.txt.

For this website I've chosen to configure my robots.txt in such a way that all robots are disallowed from all pages. As this is a website that's purely used as a course website for this course, I do not see any benefit in having it indexed, searchable, or anything else robots can do.

## Humans.txt
Humans.txt is a file that provides meta-data about the development team and software behind a website, amongst other things. It's a way to add information into your website that may not need to be readily available, but which can be of interest in certain cases.

In this website's human.txt-file I've categorised the information under two headers, the first being /*TEAM*/. Here I have listed my name, e-mail, and location. In the case of this particular website this information is slightly redundant, as that same information already is listed in the actual websites about me-section. However, if I were to have developed this website for someone else, it would be a way for me as a developer to have my own information listed and keeping some credit, without bloating the actual visible website with information that most visitors won't care about.

The other header I've chosen to use is /*SITE*/, where I've listed the language of the website, the date for the latest update, and the software I've used. I took this as an opportunity to credit the creators of the theme I'm using, by linking their website.