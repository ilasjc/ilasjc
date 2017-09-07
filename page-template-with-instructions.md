---  
layout: page # the only other option is "post", for blog posts. see the post template in the `_posts` folder.  
title: page-template # this will be the <h1> of the published page. the title here doesn't have to be the same as the name of this file.  
published: false # the only other option is "true." changing this to "true" will publish the page and add it to our sidebar list automatically. github will automatically publish any file that starts at least two sets of `---` and ends with `.md`. including "published: false" lets us work on this file until we feel it's ready to go truly live… but people can still see our drafts if they know where to look on github.  
---  

{% comment %}  
  Here's the instructions for using this template:  

  Top of this file:  
  For GitHub Pages to automatically turn a file into a webpage, the file needs to start with a few lines of metadata. The first line should be `---` and metadata should end with another `---`.  
  Anything after a `#` in the first few lines of this particular `template.md` file is a comment. You can delete it when you copy this template, but GitHub should ignore those words even if you don't.  
  
  Below this comment: 
  The `{% include toc.html %}` below will automatically add a table of contents made up of clickable links to the various headings in this file.   
  
  Headings:  
  To make a heading, start a new line with use the same number of `#` as the heading level, from h1 to h6. For accessibility reasons, the only `#h1` (or in regular html, `<h1>) on a page should be the title. So always use at least two, like:  
  `## heading level two`  
  
  I've added something called Anchor.js so that we can share URL links straight to headings inside of any of these pages. If you want to override that and make there _not_ be a link to any particular heading, add `{:.no-anchor}` to the very first line after that heading. For an example, see lines 6 and 7 on the `about.md` file and compare that heading to the rest of the headings on our published GitHub Pages page.  
  
  Notification messages:  
  
  If you want to add a notification message with automatic styling, use a regular html <p> tag and add the class "message". There's an example you can copy & paste just a few lines below.  
  
  Images:  
  
  We probably won't use many on here, but this is how to make them:  
  ![alt text](path/to/image)    
  
  So we could write:  
  ![dove breaking a chain with its beak](public/images/dove.png) and it should be turned into the regular html of <img src="public/images/dove.png" alt="dove breaking a chain with its beak">  
  
  Saving this template as a new file:  
  
  1. Delete this chunk of comments, change the metadata lines, and alter the actual body of this page. 
  2. After you're done turning this into a new page, save it with whatever title you want to have displayed on the sidebar, with `.md` as the file extension.  
  3. Remember, everything that you save can be seen on GitHub in the "code view" section, even if it's not officially "published." As long as you keep the top of this page to `published: false`, people will have to know how GitHub works to go hunting to see your drafts, but they'll be public for anyone savvy enough to find them.  
  4. Once you want to publish this, either delete the `published: false` line, or better yet, just change it to `published: true`. Remember, you should also be sure to save the file with `.md` as the file extension. That's part of how GitHub knows to treat it like it's a Markdown file and to turn it into a webpage.  
  You'll also probably want to delete this huge comment filled with instructions, but GitHub should ignore it all if you don't. It's safe to delete everything including the first `{% comment %}` to the final `{% endcomment %}` around this chucnk of instructions.  
  
{% endcomment %}

{% include toc.html %}  

<p class="message">
  Hi there! We will continue adding resources to this page.
</p>

## Resources for Everyone  

### Subsection One  

[Link text one](http://www.example.com) lets you do a thing.  
[Link text two](http://www.example.com) lets you do some other things.  

### Subsection Two  

## Resources for Librarians  

### Subsection One  

### Subsection Two   

