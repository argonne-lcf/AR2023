---

layout: home

title: Argonne Leadership Computing Facility

---
{% assign features = site.data.nav-config.toc | where: "title", "Features" %}


<div class="home--hero-wrapper">
	<div class="img-wrapper">
		<div>
			<img src="{{ site.url }}/assets/images/cover.png">
			<div class="home--hero-text">
				<h1 class="alcf">
					Argonne<br>
					<span>Leadership<br>
					Computing</span><br>
					Facility
				</h1>
				<h1 class="title">
					2022<br>
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
			    <a href="/{{ entry.url }}">
			    	<div class="image-wrapper">
			    		<div><img src="/assets/images/{{ feature[0].hero-img-source }}"></div>
			    		<div class="hover-scrim"></div>
			    	</div>
			    	<div class="content-wrapper">
			    		<h3>{{ entry.page }}</h3>
			    		<p>{{ feature[0].intro }}</p>
			    	</div>
			    </a>
			  </div>
			 
			{% endfor %}		
	</div>
</div>




<div class="home--toc-wrapper">
	<div class="content-wrapper">
		<h2>Table of Contents</h2>

		{% for item in site.data.nav-config.toc %} 
			<div class="toc-section toc-{{item.slug}}">
	      <h3>
	        <a href="{{ item.url }}" class="menuitem">
	          {{ item.title }}
	        </a>
	      </h3>

	      {% if item.subfolderitems %}
	      	{% if item.slug == "science" %}
	      		<ul class="toc-science">
		          {% for entry in item.subfolderitems %}
		          	{% if entry.page == "2022 Science Highlights" %}
			            <li class="hl">
			              <a href="{{ entry.url }}">
			              	{{ entry.page }}
			              </a>
			            </li>
			            <ul class="toc-highlights">
			              {% for highlight in site.highlights %}
		              		<li class="toc-highlight">
						      			<a href="{{ highlight.url }}">
										  		<span class="title">{{ highlight.title }}</span>
										  		<span class="pi">{{ highlight.pi }}</span>
											  </a>
											</li>
										{% endfor %}
									</ul>
			          {% else %} 
			          	<li class="not-hl">
			              <a href="{{ entry.url }}">
			              	{{ entry.page }}
			              </a>
			            </li>
			          {% endif %} 
		          {% endfor %}
		        </ul>
		      {% else %}
		      	<ul>
		          {% for entry in item.subfolderitems %}
		            <li>
		              <a href="{{ entry.url }}">
		              	{{ entry.page }}
		              </a>
		            </li>
		          {% endfor %}
		        </ul>
		      {% endif %} 
		    {% endif %} 



	      	

	      		
	      	
	        
	      

	      

	    </div>  
  	{% endfor %}

	</div>
</div>