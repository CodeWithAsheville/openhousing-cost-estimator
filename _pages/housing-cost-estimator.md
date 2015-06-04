---
ID: 12
post_title: Housing Cost Estimator
author: conantp
post_date: 2015-05-31 20:57:10
post_excerpt: ""
layout: page
permalink: >
  http://dev-open-housing-asheville.pantheon.io/housing-cost-estimator/
published: true
wp_github_commits_page_fields:
  - 'a:3:{s:15:"gc_widget_title";s:0:"";s:11:"github_user";s:0:"";s:11:"github_repo";s:0:"";}'
---
Let's build a tool that takes median hourly income for various industries in Asheville, then calculates what level of rent meets the 30% affordability standard. Then we could possibly add available properties that meet this criteria?

<a href="https://docs.google.com/spreadsheets/d/1puKFsoTROeKNmPut6LqHyEFXO24Xa8dOvd2XWYf0rJY/edit?usp=sharing">Wages by Industry Data for WNC and Asheville</a>

<a href="https://github.com/CodeForAsheville/openhousing-cost-estimator/">Github Repository</a>

Task list:
<ol>
	<li>Data Tasks
<ol>
	<li>Pull Asheville Data out of <a href="https://drive.google.com/open?id=0B0lTUpYkWIIQUEloNE12elVTU1U&amp;authuser=0">this file </a>(it's too big for Google Drive)</li>
	<li>Place extracted data into <a href="https://docs.google.com/spreadsheets/d/1puKFsoTROeKNmPut6LqHyEFXO24Xa8dOvd2XWYf0rJY/edit?usp=sharing">Wages by Industry Data for WNC and Asheville</a></li>
</ol>
</li>
	<li>Phase One Design + Development
<ol>
	<li>For each industry listed in the data, calculate the 30% number for "affordability" and display a table</li>
</ol>
</li>
	<li>Phase Two Development
<ol>
	<li>Consider proportion of each industry - what is actually "affordable" for most of Asheville?</li>
</ol>
</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

<iframe src="http://codeforasheville.github.io/openhousing-cost-estimator/" width="100%" height="500px"></iframe>