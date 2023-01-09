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
          <li class="splide__slide"> <img src="1.jpg" /></li>
          <li class="splide__slide"> <img src="2.jpg" /></li>            
      </ul>
  </div>
</div>

<div id="secondary-slider" class="splide">
  <div class="splide__track">
      <ul class="splide__list">         
          <li class="splide__slide">        
            <img src="1_thumbnail.jpg" />            
          </li>
          <li class="splide__slide">        
            <img src="2_thumbnail.jpg" />            
          </li>
      </ul>
  </div>
</div>

<script>
	var secondarySlider = new Splide('#secondary-slider', {
		rewind      : true,
		fixedWidth  : 64,
		fixedHeight : 64,
		isNavigation: true,
		gap         : 3,
		focus       : 'center',
		pagination  : false,
		cover       : false,
	  	arrows     : false,
	} ).mount();

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