---
layout: page

---
I am the principal research scientist at an applied physics laboratory which focuses on parallel processing software development for machine learning, image processing, and scientific computing.

I have a background in Physics, Applied Mathematics, and Computational Biochemistry. I had been a capable coder in BASIC, Maple, and Matlab for years before really coming into my own as a developer after discovering how much tackling science projects with Python makes me happy.  So I hacked my way through graduate school and started an applied physics laboratory after leaving my position as a research scientist at the University of Washington.

Since founding my company I have stayed busy as a tutor and technical consultant while building and refining my skills as a scientist and engineer through online courses and small research projects.

Welcome to my blog!

<div class="home">

  <ul class="posts">
    {% for post in site.posts %}
      <li>
        <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        <br>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>

</div>



<!-- ---
layout: page
title: Willkommen in der Laboratorium!
tagline: Research Blog of [WG-APL](https://github.com/wgapl)
---
{% include JB/setup %} -->


<!-- Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:

    title : My Blog =)

    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
 -->
