---
layout: post
category: rambling
tags: [github pages]
---
Getting this site up and running was easy. But, I had to go fiddle here and tweak there. Before I knew it the afternoon was at an end.


I decided to create accounts on [google analytics](http://www.google.com/analytics/) and [disqus](http://codespear.disqus.com/).  _Disqus_ is new to me, but it looks quite interesting.  

Other cool things I hope to learn more about is [jekyll](http://jekyllrb.com/), [markdown](http://daringfireball.net/projects/markdown/syntax) and [liquid](http://liquidmarkup.org/).

Strictly it is not required, but I thought it would be nice to host the site locally. Because I am running on Windows, this could be complicated. However Madhur Ahuja saved me a lot of time with his [solution](http://www.madhur.co.in/blog/2013/07/20/buildportablejekyll.html). After downloading the [dropbox](https://www.dropbox.com/) file, it all works great.

I even reasonably close to wysiwig experience; able to preview on [localhost](http://localhost:4000/).  When I save a change a file, the local deployment updates without me having to restart it. Neat.  

Here the script I use -- I called it _serve.cmd_:
{% highlight bat %}
set path=c:\programs\jekyll\ruby\bin;c:\programs\jekyll\devkit\bin;c:\programs\jekyll\Python\App;%path%;
jekyll server --drafts --watch
{% endhighlight %} 	

My first impression of [github pages](http://pages.github.com/) is that I have at last a blogging solution where I can:
 * write content using simple text files  
 * control the formatting
 * use GitHub to manage the content
 * embed gists the [easy way](https://gist.github.com/benbalter/5555251)
 * use [latex expressions](http://christopherpoole.github.io/using-mathjax-on-github-pages) for equations
 * have nice [highlighting for code snippets](http://jekyllrb.com/docs/templates/) using [pygments](http://pygments.org).
