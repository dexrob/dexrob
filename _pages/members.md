---
layout: page
title: Members
permalink: /members/
---

<style type="text/css">
	ul {
		list-style-type:none;
	}
	li {
		float: left;
	}
	.member_holder {
		display: block;
		height: 150px;
		width: 150px;
		margin-left: 20px;
		margin-right: 20px;
	}
	.member_img {
		height: 80%;
		border-radius: 50%;
	}
	.icon {
		height:20px;
		width: 20px;
		margin-left:15px;
		margin-top:5px;
	}
	.alumni_list {
		display: block;
		padding-top: 80px;
	}
</style>
<ul>
	{% for member in site.data.members %}
	{% if member.alumni == false %}
	<li class="members_li">
			<dev class="member_holder">
			<img class="member_img" src="../assets/imgs/members/{{member.avatar}}">
			<a href="">{{member.name}}</a> <br>
			{{member.description}}<br>
			<a href="{{member.google_scholar}}">
				<img class="icon" src="../assets/imgs/google_scholar.png">
			</a>
			<a href="https://github.com/{{ member.github_username| cgi_escape | escape }}" style="float:left;">
				<img class="icon" src="../assets/imgs/git.png">
			</a>
			<a href="mailto:{{member.email}}" style="float:left;">
				<img class="icon" src="../assets/imgs/mail.png">
			</a>
		</dev>
	</li>
	{% endif %}
	{% endfor %}
</ul>
<!-- <dev class="alumni_list">
 <h2> Alumni </h2>
<ol>
	{% for member in site.data.members %}
	{% if member.alumni %}
	<li>{{member.name}} ( {{member.description}} )</li>
	{% endif %}
	{% endfor %}
</ol>
</dev> -->
