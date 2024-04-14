---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* B.S. in Economic Statistics, Hunan University, 2025 (expected)
* Outstanding Participant in the Summer Program, Center for Statistical Science, Peking University

Work experience
======
* A private investment fund: Quantitative Researcher
  * Factor Mining.

* A private investment fund: FoF Researcher
  * Equity Fund Quantitative Screening and Analysis (Long-Only and Hedge Strategies): Reconstructed the entire process of fund research and access, saving approximately 50% of the time spent on fund selection; developed strategy classification tools, achieving an accuracy rate of over 90% for classifying any mainstream strategy fund; developed a screening scoring system, with the top 10% of selected funds having an annualized excess return of approximately 5% relative to the average of the same category 
  * Developed tools for automated net asset value (NAV) analysis, successfully recommending over 20 funds for inclusion in a whitelist, aiding the fund selection and configuration for a FOF account over three quarters 
  * Implemented the BARRA risk model for A-shares using optimized techniques (via CVXPY), including 19 primary factors, 31 industry factors, and 1 country factor; performed portfolio risk evaluations and performance attribution, with primary factor returns showing a T-value greater than 2 in approximately 60% of the periods

* China Securities: Quantitative Researcher
<!--
  * Developed an automated factor mining API that evaluates factor performance metrics such as information coefficient (IC), information ratio (IR), and turnover rate. The API also generates risk indicators like the Sharpe ratio and maximum drawdown ratio, facilitating in-depth research on volume-price factors 
  * Conducted literature and research report reviews to produce quantitative reports; evaluated CAPM-Beta in the Chinese market, executed single-factor tests on valuation factors through regression analysis, IC value computation, and stratified backtesting; analyzed the efficacy of factors across different industries, time periods, and market capitalization intervals
-->
Skills and Interests
======
* Skills: Proficient in Python (Pandas, Numpy, Matplotlib, etc.), R, SAS, basic C++, basic Linux, Tableau, Think-cell
* Languages: Chinese (native), English (fluent: CET4, CET6, TOEFL)
* Interests: Football (city-level competition champion), Guitar (five years of learning experience)
* Others: GitHub project [Intro to Quantitative Finance](https://github.com/Barca0412/Introduction-to-Quantitative-Finance) received 100+ stars, Co-founder of Career Partner (2k+ followers)

Projects
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Essays
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>



<!--
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
