---
layout: default
title: Home
---

# Spencer Davis

**Software Engineer // Full-Stack Developer**

I specialize in building modern web applications with a focus on clean, maintainable code. My background in chemical engineering gives me a structured, problem-solving mindset that I bring into software development.

![Profile Image](/assets/images/portrait.png)

## Projects

Here are some of my projects, showcasing my experience with various technologies:

{% assign sorted_repos = site.github.public_repositories | sort: 'created_at' %}
{% for repo in sorted_repos %}

- **[{{ repo.name }}]({{ repo.html_url }})** ({{ repo.language }})
  {% endfor %}

## Get in Touch

Interested in working together or discussing a project?  
📩 [Email Me](mailto:sdavis26@me.com) | [GitHub](https://github.com/spencerdavis226) | [LinkedIn](https://www.linkedin.com/in/davisspencer/)
