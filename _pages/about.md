---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a [YOUR_TITLE / e.g., Ph.D. student / Researcher] at [YOUR_INSTITUTION]. My research interests include [YOUR_RESEARCH_INTERESTS]. 

<!-- Google Scholar citation badge (replace YOUR_GOOGLE_SCHOLAR_ID) -->
<!-- <a href='https://scholar.google.com/citations?user=YOUR_GOOGLE_SCHOLAR_ID'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->


# 🔥 News
- *[YEAR.MONTH]*: &nbsp;🎉 [YOUR_NEWS_ITEM]

# 📝 Publications 

<!-- ========== Featured Paper (with image) ========== -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[VENUE e.g. CVPR 2024]</div><img src='images/paper1.png' alt="paper thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PAPER_TITLE](PAPER_PDF_URL)

**[YOUR_NAME]**, Co-Author1, Co-Author2

<!-- [**Project Page**](PROJECT_URL) -->
- [PAPER_ONE_LINE_SUMMARY]
</div>
</div>

<!-- ========== Additional papers (list style) ========== -->
- [PAPER_TITLE_2](PAPER_URL_2), Author1, **[YOUR_NAME]**, Author3, **VENUE 2023**

# 🎖 Honors and Awards
- *[YEAR.MONTH]* [AWARD_NAME], [INSTITUTION]

# 📖 Educations
- *[START - END]*, [DEGREE], [MAJOR], [UNIVERSITY]
- *[START - END]*, [DEGREE], [MAJOR], [UNIVERSITY]

# 💬 Invited Talks
- *[YEAR.MONTH]*, [TALK_TITLE], [VENUE/CONFERENCE]

# 💻 Internships / Work Experience
- *[START - END]*, [ROLE], [COMPANY/LAB], [LOCATION]