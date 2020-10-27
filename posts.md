---
layout: default
title: Posts
---

{% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}

<section class="section-content article-post">
	<div class="col-md-12">
		<h2>Blog</h2>
		<table class="table table-striped">
			<tbody>
				{% for post in site.posts %}
				<tr>
					<td>
						<h4><a href="{{ post.url | absolute_url }}">{{ post.title | escape }}</a></h4>
						<div>{{ post.excerpt }}</div>
					</td>
					<td>
						{{ post.date | date: "%b %-d, %Y" }}
					</td>
				</tr>
				{% endfor %}
			</tbody>
		</table>
	</div>
</section>
