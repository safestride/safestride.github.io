---
layout: page
title: About
image: assets/images/plots.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Our goal</h2>
		</header>
		<p>Safestride is a platform that aims to combine walking route mechanisms with local DC Crime data.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/plots.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Data</h3>
				</header>
				<p>SafeStride sources data primarily from Metro PD, through the website opendata.dc.gov. 
				Every night at midnight, crime events from the past day are released to the public to view.
				SafeStride scrapes this data, and inserts it into our own database. When users are ready to 
				open the application, they will see these recent crimes. They will be able to customize the
				date range for the crimes that they are interested in, and can additionally use the reporting
				feature to fill in the map if they feel it is incomplete. </p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/routes.png %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Walking Routes</h3>
				</header>
				<p>The other primary feature of SafeStride is to provide safe walking directions to a user. 
				Based on their preferences (defined in the settings page), users are given customized walking 
				directions to their destination. Simply by typing in a destination, our Dijkstra's-based algorithm 
				will determine which edges (or streets) are most in-line with the user's preferences, and will 
				return three potential walking routes for the user to choose between. These routes are scored 
				through a combination of (1) preferences, (2) decay over time, and (3) decay over distance. Of 
				the three walking routes provided, one will be optimized for time, one for distance, and one 
				with a combination of the two. </p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/directions.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Directions</h3>
				</header>
				<p>When users are ready to select a given walking route, they can click the "go" button seen in 
				the image above. This will take users to a new screen, where they can see their walking route and 
				additionally access turn-by-turn directions of the walking route. Included in this screen is a 
				plotting of crimes nearby the route that have happened over the past three days. In these areas, users 
				can pay extra attention to their safety. </p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Additional Features</h2>
		</header>
		<p>One additonal feature of SafeStride is our explore page. Seen in our explainational video, this explore 
		page allows users to view local monuments and be taken to those monuments safely. Monuments listed in this 
		explore page include the White House, the National Cathedral, and Union Station. A second additional feature 
		is for users to customize the crimes they care about. Users can choose to toggle on or off the rendering of 
		any crime category, and can additional choose how "old" the crimes they are viewing are. By default, crime age 
		is 15 days. However, users can set this age to be between 1 and 90 days if they choose. </p>
		<ul class="actions">
			<li><a href="generic.html" class="button next">Learn More</a></li>
		</ul>
	</div>
</section>

</div>
