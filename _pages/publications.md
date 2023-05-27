---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
##Published Articles 
*Eunsoo Kim, **MengQi(Annie) Ding**, Shijie Lu and Xin (Shane) Wang (2023), “Does Topic Consistency Matter? 
A Study of Critic and User Reviews in the Movie Industry”, Journal of Marketing, 87(3), 428–450. </i> Full text available at: <a href = "https://journals.sagepub.com/doi/abs/10.1177/00222429221127927"> JGR</a>



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
