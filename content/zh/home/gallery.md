---
widget: blank
headless: true
weight: 30
#gallery_item:
# - album: "/"
#   image: 1.jpg
#   caption: caption1
# - album: "/"
#   image: 2.jpg
#   caption: caption2
   
   
# {{< gallery album="/" >}}
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@latest/dist/css/splide.min.css"> 
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@latest/dist/js/splide.min.js"></script>

<section id="image-carousel" class="splide" aria-label="Beautiful Images">
  <div class="splide__track">
		<ul class="splide__list">
			<li class="splide__slide">
				<img src="https://images.unsplash.com/photo-1670992367974-d11122d8e8c8?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" alt="">
				<div>
					Description 01
				</div>
			</li>


			<li class="splide__slide">
				<img src="https://images.unsplash.com/photo-1670882410130-4f279af7ecd1?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" alt="">
				<div>
					Description 02
				</div>
			</li>
		</ul>
  </div>
</div>


<script>
document.addEventListener( 'DOMContentLoaded', function () {
  new Splide( '#card-carousel', {
		perPage    : 2,
		breakpoints: {
			640: {
				perPage: 1,
			},
		},
  } ).mount();
} );
</script>

{{% cta cta_link="./people/" cta_text="团队成员" %}}