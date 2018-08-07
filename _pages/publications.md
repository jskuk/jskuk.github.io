---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Publications
======
Zoltan Hajnal, **John Kuk**, and Nazita Lajevardi. “We All Agree: Strict Voter ID Laws Disproportionately Burden Minorities.” *The Journal of Politics* 80.3 (2018): 1052–1059
[Link to paper](https://www.journals.uchicago.edu/doi/abs/10.1086/696617)

**John Kuk**, Deborah Seligsohn, and Jack Jiakun Zhang. “The Effect of Rising Import Competition on Congressional Voting Towards China." *Journal of Contemporary China* 27.109 (2018): 103–119
[Link to paper](https://www.tandfonline.com/doi/abs/10.1080/10670564.2017.1363024)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
