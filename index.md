---
layout: default
title: Home
---

{%- if site.parts.size > 0 -%}
    {%- for post in site.parts -%}
			<section id="one" class="wrapper style2 special">
				{{post.content}}
			</section>
		{%-endfor-%}
{%-endif-%}

<!-- One
<section id="one" class="wrapper style2 special">
	<header class="major">
		<h2>
		We give rides to Galena, Cedar Rapids, <br/>quad cities, Iowa city, Chicago
		</h2>
	</header>
</section>

 Two
<section id="two" class="wrapper">
	<div class="inner alt">
		<section class="spotlight">
			<div class="image"><img src="assets/images/pic01.jpg" alt="" /></div>
			<div class="content">
				<h3>Magna sed ultrices</h3>
				<p>Morbi mattis ornare ornare. Duis quam turpis, gravida at leo elementum elit fusce accumsan dui libero, quis vehicula lectus ultricies eu. In convallis amet leo non sapien iaculis efficitur consequat lorem ipsum.</p>
			</div>
		</section>
		<section class="spotlight">
			<div class="image"><img src="assets/images/pic02.jpg" alt="" /></div>
			<div class="content">
				<h3>Ultrices nullam aliquam</h3>
				<p>Morbi mattis ornare ornare. Duis quam turpis, gravida at leo elementum elit fusce accumsan dui libero, quis vehicula lectus ultricies eu. In convallis amet leo non sapien iaculis efficitur consequat lorem ipsum.</p>
			</div>
		</section>
		<section class="spotlight">
			<div class="image"><img src="assets/images/pic03.jpg" alt="" /></div>
			<div class="content">
				<h3>Aliquam sed magna</h3>
				<p>Morbi mattis ornare ornare. Duis quam turpis, gravida at leo elementum elit fusce accumsan dui libero, quis vehicula lectus ultricies eu. In convallis amet leo non sapien iaculis efficitur consequat lorem ipsum.</p>
			</div>
		</section>
	</div>
</section>
-->
