---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF Version Here](https://fyc1007261.github.io/files/YifanCai.pdf) (Updated in Aug. 2019)

Education
======
* B.S. in Software Engineering, Shanghai Jiao Tong University, 2016-2020
  * **Overall GPA:** 3.77 / 4.30 (88.19/100); **Major GPA:** 3.88 / 4.30 (89.95/100)
  * **Honors/Awards:** SJTU Scholarships (2016-2017 & 2017-2018), Huawei Scholarships (2017-2018)
  * **Selected Courses:** Operating Systems (4.0), Distributed Systems (4.0), Computer Architecture (4.0), etc.

# Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research experience
======
* Research Intern (Jul 2019 - Dec 2019 expected)
  * University of Pennsylvania
  * Took a first step towards understanding how disaggregated data centers might affect the design of relational databases, discussed the potential advantages and drawbacks in the context of data processing, and outlined research challenges in addressing them.
  * Modified the kernel of LegoOS (A disaggregated operating system published in OSDI’18) and deployed it on cloud machines; wrote code of nested loop join, hash join as well as grace hash join and tested their performance on disaggregated operating systems.
  * Designed benchmarks and discovered where the performance bottleneck of disaggregated systems is.
* Research Intern (Aug 2018 - Sep 2018)
  * University of Michigan
  * Built an LSTM-based solar forecasting system on keras deep learning library
  * Completed the predicting model, and the accuracy of which would be better than all of those in published papers in some specific conditions.
  * Supervisor: Prof. Xianglei Huang
* Research Assistant (Sep 2017 - Jun 2019)
  * Shanghai Jiao Tong University
  * Design a protocol in distributed network systems to do statistics cooperatively. It is the first protocol proposed to compute the probability density function in a fully distributed way.
  * Responsible for algorithm design and optimization, numerical simulations and paper writing.
  * Supervisor: Prof. Jianping He
  
Skills
======
* System software, including operating systems, networking, distributed systems, etc.
* Data analysis, including Python, SQL and basic deep learning skills.
* Web development, including Spring, React, etc.

