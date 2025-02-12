---
title: The Prosperity Public License
description: the noncommercial software license
layout: default
---

[Prosperity](versions/2.0.0.html) is a public `LICENSE` for software that makes work free for noncommercial use, with a built-in free trial for commercial users.

<h2 id=projects>Projects</h2>

<ul class="projects">
{% for project in site.projects reversed %}
<li>
    <a href="{{project.url}}">{{project.title}}</a>{% if project.description %}, {{project.description}}{% endif %}{% if project.language %}, in {{project.language}}{% endif %}
  </li>
  {% endfor %}
</ul>

<p>To list your project, send a pull request <a href="https://github.com/licensezero/prosperitylicense.com/">via GitHub</a>.</p>

<h2 id=Development>Development</h2>

License development continues in [the GitHub repository](https://github.com/licensezero/prosperity-public-license).  Feel free to open issues and send pull requests.
