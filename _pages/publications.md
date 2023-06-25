---
layout: archive
title: "Publications"
permalink: /paper/
author_profile: true
---
Eunsoo Kim, **MengQi(Annie) Ding**, Shijie Lu and Xin (Shane) Wang (2023), “Does Topic Consistency Matter? 
A Study of Critic and User Reviews in the Movie Industry”,<i> Journal of Marketing</i>, 87(3), 428–450. Full text available at: <a href = "https://journals.sagepub.com/doi/abs/10.1177/00222429221127927"> https://journals.sagepub.com/doi/abs/10.1177/00222429221127927</a> 

<font size="-1">Abstract: Online review platforms often present reviews from both critics and general users. In this research, 
the authors propose a measure called “topic consistency” to capture the degree of overlap between 
critic and user review content. High topic consistency suggests greater information recall due to 
repeated presentation of the same topics, which may increase the memorability of movie attributes 
and therefore positively affect movie demand. The authors measure the topic consistency between 
critic and user reviews using topic models and further study the financial consequences of this 
measure using data for movies released in the United States. Topic consistency is positively associated 
with subsequent box office revenue, suggesting a positive relationship between topic consistency and 
movie demand. Furthermore, the effect of topic consistency on demand is the greatest for movies with 
mediocre review ratings and when the review ratings from critics are close to those from users. Using 
lab experiments, the authors provide evidence of the causal link between topic consistency and 
consumers’ willingness to watch a movie, and support for the potential mediation through the 
information recall of reviews. Movie producers and advertisers should consider highlighting or 
inducing a central theme for critics and users to discuss, as the more the review content of critics and 
users overlaps, the higher a movie’s revenue</font>

**MengQi (Annie) Ding** and Avi Goldfarb (2023), “The Economics of Artificial Intelligence: A Marketing
Perspective”, <i>Review of Marketing Research</i>, Vol 20,13-26. Full text available at: <a href = "https://www.emerald.com/insight/content/doi/10.1108/S1548-643520230000020002/full/html"> https://journals.sagepub.com/doi/abs/10.1177/00222429221127927</a>

<font size="-1">Abstract: This article reviews the quantitative marketing literature on artificial intelligence (AI) through an
economics lens. We apply the framework in Prediction Machines: The Simple Economics of Artificial
Intelligence to systematically categorize 96 research papers on AI in marketing academia into five
levels of impact, which are prediction, decision, tool, strategy, and society. For each paper, we further
identify each individual component of a task, the research question, the AI model used, and the broad
decision type. Overall, we find there are fewer marketing papers focusing on strategy and society, and
accordingly, we discuss future research opportunities in those areas.</font>

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
