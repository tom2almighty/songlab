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
<html>
<head>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@latest/dist/css/splide.min.css"> 
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@latest/dist/js/splide.min.js"></script>
</head>
<body>
<section id="image-carousel" class="splide" aria-label="Beautiful Images">
  <div class="splide__track">
		<ul class="splide__list">
			<li class="splide__slide">
				<img src="https://images.unsplash.com/photo-1670882410130-4f279af7ecd1?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" alt="">
			</li>
			<li class="splide__slide">
				<img src="https://images.unsplash.com/photo-1670644009691-7e57accee1c1?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" alt="">
			</li>
			<li class="splide__slide">
				<img src="https://images.unsplash.com/photo-1670918532018-8e621d592758?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80" alt="">
			</li>
		</ul>
  </div>
</section>
</body>

<script>
  document.addEventListener( 'DOMContentLoaded', function () {
    new Splide( '#image-carousel' ).mount();
  } );
</script>

{{% cta cta_link="./people/" cta_text="团队成员" %}}
</html>