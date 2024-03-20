---

layout: home

title: Argonne Leadership Computing Facility

---
{% assign features = site.data.nav-config.toc | where: "title", "Features" %}


<div class="home--hero-wrapper">
	<div class="img-wrapper">
		<div>
			<!-- <img src="{{ site.url }}/assets/images/cover.png"> -->
			<!-- poster="{{ site.url }}/assets/images/cover.png"  -->
			<video autoplay loop>
				<source src="{{ site.url }}/assets/video/hypersonic.webm" type="video/webm">	
				<source src="{{ site.url }}/assets/video/hypersonic.mp4" type="video/mp4">
  				Your browser does not support the video tag.
			</video>
			<div class="home--hero-text">
				<h1 class="alcf">
					Argonne<br>
					<span>Leadership<br>
					Computing</span><br>
					Facility
				</h1>
				<h1 class="title">
					2023<br>
					<span>Annual<br>
					Report</span><br>
				</h1>
			</div>
			<div class="home--hero-scrim"></div>
		</div>
	</div>
</div>

<div class="home--hero-caption">
	<small>
		Visualization of particle light cone data from Farpoint, a high-resolution cosmology simulation at the gigaparsec scale.
		<span class="credit">Image: ALCF Visualization and Data Analytics Team and the HACC Team</span>
	</small>
</div>




<div class="home--features-wrapper">
	<div class="content-wrapper">
		<h2>Features</h2>
			{% for entry in features[0].subfolderitems %}
			{% assign feature = site.pages | where: 'permalink', entry.url %}			  
			  <div class="teaser">
			    <a href="{{ site.url }}/{{ entry.url }}">
			    	<div class="image-wrapper">
			    		<div><img src="{{ site.url }}/assets/images/{{ feature[0].hero-img-source }}"></div>
			    		<div class="hover-scrim"></div>
			    	</div>
			    	<div class="content-wrapper">
			    		<h3>{{ feature[0].title }}</h3>
			    		<p>{{ feature[0].intro }}</p>
			    	</div>
			    </a>
			  </div>		 
			{% endfor %}		
	</div>
</div>




