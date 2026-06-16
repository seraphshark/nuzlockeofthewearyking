---
title: Home
layout: home
nav_order: 1
---
<html>
<link href="{{ site.baseurl }}/assets/css/faketweet.css" rel="stylesheet">

  {% for post in site.posts %}
  {% assign author = site.authors[post.author] %}
    <div class="twt">
      <div class="twt-header">
      	<div class="twt-icon-container"><img class="twt-icon" src="{{ site.baseurl }}/icons/{{ author.icon }}"></div>
      	<div class="twt-id"><span class="twt-name">{{ author.name }} </span><br><span class="twt-handle">@{{ post.author }}</span></div>
   		</div>
   		<div class="twt-content">
      	<app-content><span> {{ post.content }} </span></app-content>
   		</div>
   		<div class="twt-timestamp">{{ post.post_time }} · {{ post.post_date }}</div>
   	<hr class="twt-sep">
   <div class="twt-stat1"><strong>0</strong> Retweets &nbsp;&nbsp; <strong>0</strong> Quote Tweets &nbsp;&nbsp; <strong>0</strong> Likes </div>
	   {% if reply == 'true' %}
	   <hr class="twt-sep-reply">
	  	<app-reply>
		    <div class="twt-replybox">
		      <div class="twt-icon-replycontainer">
		        <img class="twt-icon" src="{{ site.baseurl }}/icons/{{ post.reply_icon }}">
		      </div>
		      <div class="twt-replycontainer">
		        <span class="twt-name">{{ post.reply_author }}</span>
		        <span class="twt-handle">@{{ post.reply_handle  }} · Jan 2, 2024 </span>
		        <span class="twt-handle">Replying to</span>
		        <span class="twt-hl"> @{{ post.author }}</span>
		        <div class="twt-replycontent">
		          <app-content>
		            <span>{{ post.reply_text }}</span>
		          </app-content>
	        	</div>
		{% endif %}
	</div>
  {% endfor %}
</html>
