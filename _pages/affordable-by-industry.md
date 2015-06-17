---
ID: 61
post_title: 'Industry Affordability: Crowded House'
author: conantp
post_date: 2015-06-04 18:18:07
post_excerpt: ""
layout: page
permalink: >
  http://dev-open-housing-asheville.pantheon.io/affordable-by-industry/
published: true
wp_github_commits_page_fields:
  - 'a:3:{s:15:"gc_widget_title";s:0:"";s:11:"github_user";s:0:"";s:11:"github_repo";s:0:"";}'
---
<h1 class="c1"><span class="c4">Industry Affordability Group:</span></h1>
<p class="c1"><img title="" src="https://lh6.googleusercontent.com/CnpwQvd5x2UPR3vLqlR_SSIt1hljkp9x3lVyVRXlSGHMRrsLTC9VoZ0neaiQQAEhib9im3apxYuRTBbhOByUH_XAzY0kHNfUy1VMpTtjIQZU6ZzQmIsTOea_V6bkfMYmta2RS9g" alt="CrowdedHouse.png" /></p>
<p class="c1"><span class="c9">Affordable housing standards are typically based upon the median household income. We set out to build a visualization that provides a deeper perspective on the issue of affordability - by breaking down Asheville into income-based groups, then calculating the number of renters required to make rent for various rental prices. We supplemented this information by identifying the proportion of the local workforce that falls into each income category.</span></p>

<h2 class="c1 c13"><a name="h.88119p6bjgz5"></a>Next Steps:</h2>
<ol class="c3 lst-kix_owww17vbytac-0 start" start="1">
	<li class="c1 c8"><span class="c9">Interactive version of graph</span></li>
</ol>
<ol class="c3 lst-kix_owww17vbytac-1 start" start="1">
	<li class="c1 c2"><span class="c9">Sliders for rent price</span></li>
</ol>
<ol class="c3 lst-kix_owww17vbytac-0" start="2">
	<li class="c1 c8"><span class="c9">More detailed information</span></li>
</ol>
<ol class="c3 lst-kix_owww17vbytac-1 start" start="1">
	<li class="c1 c2"><span class="c9">Specific occupations</span></li>
	<li class="c1 c2"><span class="c9">Overlaying the City affordability standards / incentive packages for these price levels</span></li>
	<li class="c1 c2"><span class="c9">Percentage of renters vs total population</span></li>
</ol>
&nbsp;

&nbsp;
<h2>Project Introduction</h2>
Most affordable housing levels are based on the AMI (Average Median Income) for Buncombe County.

However, there's more to the story - many industries in Asheville pay wages far below the county-wide median, and these people have even greater difficulty finding housing in Asheville.

US Dept. of Labor Bureau of Labor Statistics (Wage Data): http://www.bls.gov/oes/current/oes_11700.htm

Here's a report, used by MHO, that does what I'm suggesting - but the data is a bit out of date. We can build a tool that does the same thing, but pulls data directly from the Dept. of Labor!

<a href="http://dev-open-housing-asheville.pantheon.io/wp-content/uploads/2015/05/MHO-Abbreviated-Presentation-Oct-2012-for-Leadership-Asheville-Seniors.pdf">MHO Abbreviated Presentation Oct 2012 for Leadership Asheville Seniors</a>

Let's build a tool that takes median hourly income for various industries in Asheville, then calculates what level of rent meets the 30% affordability standard. Then we could possibly add available properties that meet this criteria?

<a href="https://docs.google.com/spreadsheets/d/1puKFsoTROeKNmPut6LqHyEFXO24Xa8dOvd2XWYf0rJY/edit?usp=sharing">Data: Wages by Industry Data for WNC and Asheville</a>

<a href="https://github.com/CodeForAsheville/openhousing-industry-affordability">Github Repository</a>

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
	<li>Consider proportion of each industry - what is "affordable" for X percent of Asheville?</li>
</ol>
</li>
</ol>
&nbsp;