---
layout: page
title: Members
permalink: /members/
---

<!-- <ul>
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
</ul> -->


<style type="text/css">
	ul {
		list-style-type:none;
	}
	/* li {
		float: left;
	} */
	/* comment above for proper alignment */

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
	.member_group {
		/* Use grid mode helps with alignment! */
		display: grid;
		width: 100%;
		margin: auto;
	}
	.member_holder {
		display: block;
		height: 150px;
		width: 150px;
		margin-left: 20px;
		float: left;
		padding-bottom: 10%;
	}

</style>



<div class="member_group">
<h2>PI</h2>
<ul>
	{% for member in site.data.members %}
	{% if member.position == 0 %}
	<li>
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
</div>

<div class="member_group">
<h2>Staff members</h2>
<ul>
	{% for member in site.data.members %}
	{% if member.position == 1 %}
	<li>
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
</div>

<div class="member_group">
<h2>PhD students</h2>
<ul>
	{% for member in site.data.members %}
	{% if member.position == 2 %}
	<li>
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
</div>

<div class="member_group">
<h2>Attached students</h2>
<ul>
	{% for member in site.data.members %}
	{% if member.position == 3 %}
	<li>
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
</div>

