---
layout: default
title: Hello
---

<br>
# Hi, I'm Owen, a product designer at [Five9](https:www.five9.com), working on conversational experiences and AI. <br>Previously at Inference.
#### Based in San Ramon, CA
<br>
---

## Projects

{% for project in site.projects %}
  <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>

  <p>{{ project.description }}</p><br>
{% endfor %}




<!-- [Bear Blog](https://bearblog.dev/) is *"a blogging platform where words matter most"*. 

This is a port of it's theme to Jekyll, with some tweaks. So you can use GitHub Pages to host your blog while getting the same awesome Bear Blog feels.

**Stop worrying about the style, focus on your writing.**

- Looks great on *any* device
- Tiny, optimized, and awesome pages
- No trackers, ads, or scripts, *did I mention minimal already?*
- Auto light and dark themes
- Tag support, to filter blog pages
- Quick, *15 minute* setup
- Gallery view for your images
- Code highlighting

Have a look around, this website is already themed with **jekyllBear**. If you like it, head over to the GitHub [repository](https://github.com/knhash/jekyllBear) for installation instructions. -->
