---
layout: default
title: Home
---

<section class="intro fade-in">

<img src="/assets/profile.jpg"
     alt="Profile photo of Ashutosh Sharma"
     class="profile-photo">

# Ashutosh Sharma

<p class="tagline">
Graduate student in mathematics, with a strong interest in pure and theoretical research.
</p>

<p style="margin-top:16px;">
<a href="/assets/Ashutosh_Sharma_CV.pdf" class="cv-button" target="_blank">
Download CV
</a>
</p>

</section>

<section class="content card fade-in">

I am currently pursuing my master’s degree in mathematics at
[Indian Institute of Technology Delhi](https://www.iitd.ac.in).

My academic interests lie primarily in pure mathematics, particularly in
number theory, algebra, and analysis. I am especially drawn to problems
that emphasize structure, rigor, and conceptual elegance.

This website serves as my academic homepage, where I document my studies,
research interests, and occasional mathematical reflections.

</section>

<section class="content fade-in">

## Recent Writing

{% for post in site.posts limit:3 %}
<div class="blog-post">
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
<div class="post-date">{{ post.date | date: "%B %Y" }}</div>
<p>{{ post.excerpt }}</p>
</div>
{% endfor %}

</section>
