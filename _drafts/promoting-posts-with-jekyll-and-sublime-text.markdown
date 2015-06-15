---
layout: 
title: Promoting Posts with Jekyll and SUblime Text
categories: []
tags: []
published: True

---
# Jekyll thoughts

Spending a little bit of time with Jekyll, it seems reasonably easy to setup. Creating a site and then automating that site into a web server, in my case I'm using Apache. It's all quite easy.

Now I have a site, running on a Virtual Machine, how do I send my posts directoly onto the web server with little or no fuss.

# The bits

For this to work, call this my work flow, I need the following:

- Sublime Text
- SFTP package using Sublime Text
- Jekyll package using Sublime Text
- Unix scripts

The workflow looks something like:

1. Create a draft in Sublime Text using the Jekyll drafts plugin.
2. When the draft is complete, use the command to transfer the draft into the post folder
3. Use the FTP package to transfer the file into the source directory, posts directory.
4. The Jekyll watch process will then pick up the post, transfer it to the website and translate teh Markdown to HTML as appropriate.

Let see how this works.

