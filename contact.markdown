---
layout: single
title: Contact
permalink: /contact/
---

The best way to reach me:

- **Email:** [{{ site.email }}](mailto:{{ site.email }})
{% if site.github_username -%}
- **GitHub:** [github.com/{{ site.github_username }}](https://github.com/{{ site.github_username }})
{% endif -%}
{% if site.twitter_username -%}
- **Twitter/X:** [@{{ site.twitter_username }}](https://twitter.com/{{ site.twitter_username }})
{% endif -%}
{% if site.linkedin_url != "" -%}
- **LinkedIn:** [{{ site.linkedin_url }}]({{ site.linkedin_url }})
{% endif -%}

Whether it's a freelance project, a question about something I've built, or just to say hi — I read everything.

You can also follow the blog via [RSS]({{ '/feed.xml' | relative_url }}).
