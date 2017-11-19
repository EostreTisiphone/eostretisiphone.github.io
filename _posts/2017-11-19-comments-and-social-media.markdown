---
layout: post
title: "Comments and Social Media"
categories: web-development
---
## Disqus
As this website is a static website it does not have any internal way of handling comments, so to be able to have people comment on the posts this function has to be out sourced. The way I've chosen to do this is by implementing support for Disqus. Out sourcing functions like this have a lot of benefits, such as it being very easy, and I don't have to deal with any security surrounding log-ins. 

As the theme I've chosen to work with already had a support for Disqus built in, all I had to do was create an account and add my shortname to the website's _config.yml.

The theme handles disqus-comments by using an include called disqus_comments.html, which is added to each file of the type "post" if a Disqus shortname is defined in the site's config. The default setting is for comments to be turned on, but they can easily be turned off for separate posts by adding frontmatter to the post in question.

## Open Graph
Open Graph is a system used for sharing content on social media in a nice-looking way. I'm sure most people have encountered someone sharing an article somewhere, and the preview image being something completely irrelevant to the content being shared. Open Graph gives the author of a page control over what will be shown in the preview when sharing conent.

There are a lot of tags you can add to your Open Graph-metadata, and not all of them are required. The four properties that are not optional is a title, type, image and URL. Optional properties include such as an audio/video file to complement the linked object, a short description, and the main site name.