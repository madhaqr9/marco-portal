---
layout: default
title: MARCO Portal Project Log
tagline: 
---
{% include JB/setup %}

<div class="row">
	<div class="span12">
		<img src="{{BASE_PATH}}/assets/img/windmill-ocean.jpg"/>
	</div>
	<div class="span12">
		<p class='big-text'>Providing insight into the development of the Mid-Atlantic Ocean Data Portal</p>
    <p><a class='btn' href="http://portal.midatlanticocean.org">Go to the MARCO Portal</a></p>
	</div>
</div>

<hr/>

<div class="row">
  <div class="span3">
    <h2>Latest Dev News</h2>
  </div>	
  {% for post in site.posts limit:2 %}
  <div class="span3">
    <h3><a href="{{BASE_PATH}}{{ post.url }}">{{ post.title }}</a></h3>
	<div class="date">{{ post.date | date_to_long_string }}</div>
    <p>{{ post.content | strip_html | truncatewords: 25 }}</p>    
    <p class="pull-right">
      <a href="{{BASE_PATH}}{{ post.url }}">Read more</a>
    </p>
  </div>
  {% endfor %}
  <div class="span2">
    <p><a class='btn' href="{{BASE_PATH}}/archive.html">Archives</a></p>
    <p><a class='btn' href="{{BASE_PATH}}/categories.html">Categories</a></p>
    <p><a class='btn' href="{{BASE_PATH}}/tags.html">Tags</a></p>
    <p><a href="http://feeds.feedburner.com/MarcoPortalDevelopmentLog"><img height="20" width="20" src="{{BASE_PATH}}/assets/img/feed-icon-28x28.png"/></a></p>
  </div> 
</div>

<hr/>

<div class="row">
  <div class="span3">
    <h2>Portal Project Timeline</h2>
  </div>
  <div class="span3">
  	<h3>Release 2 - September 2012</h3>
  	<p><i>Complete!</i></p>
    <p>Launch of the revamped portal website. Preliminary data catalog and mapping tool with sector-specific parameters and spatial filters.  Additional datasets with stakeholder vetting.</p>
  </div>	
  <div class="span3">
  	<h3>Release 3 - Late Fall 2012</h3>
    <p><i>Complete!</i></p>
  	<p>More data.  User account and print feature.  Improved spatial filters based on stakeholder feedback.  Ability to design and generate reports.</p>
  </div>  
  <div class="span3">
  	<h3>Release 4 - June 2013</h3>
  	<p>Scenario planning/spatial filter features using lease blocks as the planning units.  Additional datasets.</p>
  </div>  
</div>

<hr/>

<div class="row">
	<div class="span10">
		<div class="row blocks">
			<div class="span5">
				<div class="well">
					<h3>Project Links</h3>
					<p>
						<ul>
							<li><a href="http://midatlanticocean.org/map_portal.html">What is the MARCO Portal?</a></li>							
							<li><a href="{{BASE_PATH}}/technology.html">Technology stack</a></li>
							<li><a href="http://github.com/ecotrust/marco-portal">GitHub site (code and issue tracking)</a></li>							
						</ul>
					</p>
				</div>
			</div>
      <div class="span5">
        <div class="well">
          <h3>Development Team</h3>
          <p>
            <ul>
              <li>The Nature Conservancy</li>              
              <li>Ecotrust</li>              
              <li>Rutgers - Center for Remote Sensing and Spatial Analysis</li>
              <li>Monmouth University</li>
            </ul>
          </p>
        </div>
      </div>
		</div>
	</div>
</div>