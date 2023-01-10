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

<div id="primary-slider" class="splide">
  <div class="splide__track">
      <ul class="splide__list">
          <li class="splide__slide"> <img src="https://images.unsplash.com/photo-1671243396019-a47f031d20e9?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" /></li>
          <li class="splide__slide"> <img src="https://images.unsplash.com/photo-1670992367974-d11122d8e8c8?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" /></li>            
      </ul>
  </div>
</div>


<script>

	// Create the main slider.
	var primarySlider = new Splide( '#primary-slider', {
		type       : 'fade',
		heightRatio: 1,
		pagination : false,
		arrows     : false,
		cover      : true,
	} );

	// Set the thumbnails slider as a sync target and then call mount.
	primarySlider.sync( secondarySlider ).mount();
</script>

{{% cta cta_link="./people/" cta_text="团队成员" %}}