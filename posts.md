---
layout: default
title: Posts
---

{% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
{% assign posts = site.posts | sort:"starts" | reverse %}

<section class="section-content article-post">
	<div class="col-md-12">
		<h2>Blog</h2>
		<table class="table table-striped">
			<tbody>
				{% for post in posts %}
				<tr>
					<td>
						<h4><a href="{{ post.url | absolute_url }}">{{ post.title | escape }}</a></h4>
						<div>{{ post.excerpt }}</div>
					</td>
				</tr>
				{% endfor %}
			</tbody>
		</table>
	</div>
</section>
