---
layout: post
title:  "Getting started with Surge"
date:   2015-06-10 16:22:20
categories: jekyll update
---
Surge has been built from the ground up for <a href="https://blog.andyet.com/2015/01/22/native-web-apps">native web application</a> publishing and is committed to being the <strong>best way</strong> for Front-End Developers to put HTML5 applications into production.

Deploy something—anything—right now, for free:

<figure>
  <div class="embed-container">
    <iframe src="https://www.youtube.com/embed/-EjdMvYPSVU?enablejsapi=1&amp;modestbranding=1&amp;autoplay=0&amp;rel=0&amp;showinfo=0&amp;theme=light&amp;color=white" allowfullscreen="allowfullscreen" async="async" defer="defer" frameborder="0"></iframe>
  </div>
  <figcaption>Surge makes it easy for developers to deploy projects to a production-quality CDN through <a href="http://gruntjs.com">Grunt</a>, <a href="http://gulpjs.com">Gulp</a>, <a href="http://npmjs.org">npm</a>.</figcaption>
</figure>

With Surge, you’ll easily have something online quickly. First install the command line tool using npm and then run surge within any directory you wish to publish onto the web. All you need to get started is:

1. First, ensure you have a recent version of [Node.js](http://nodejs.org)
2. Then, install Surge using npm by running the following command:
   ```
   npm install --global surge
   ```
   <small>You may need to preface this command with `sudo`</small>
3. Now, run <code>surge</code> from within any directory, to publish that directory onto the web.

That’s it! Running surge inside the directory you want to deploy will get your started. You’ll be able to create an account right from the command line, deploy, and host your site for free on Surge.


<figure>
  <img src="https://surge.sh/images/help/getting-started-with-surge.gif">
  <figcaption>To deploy, just run surge within the directory you want online. Here, a <a href="adding-a-custom-domain">custom domain</a> has been setup instead of the suggested <em>surge.sh</em> subdomain</figcaption>
</figure>

Check out how to [add a `CNAME` file](https://surge.sh/help/remembering-a-domain) to remember your subdomain, or how to [add your own, custom domain](https://surge.sh/help/adding-a-custom-domain) for free.
