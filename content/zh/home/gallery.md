---
widget: blank
headless: true
weight: 30
gallery_item:
 - album: "/"
   image: 1.jpg
   caption: caption1
 - album: "/"
   image: 2.jpg
   caption: caption2
---
{{< gallery album="/" >}}
<body>
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@latest/dist/js/splide.min.js"></script>

<div id="image-slider" class="splide">
  <div class="splide__track">
		<ul class="splide__list">
			<li class="splide__slide">
				<img src="1.jpg">
				<div>
					Description 01
				</div>
			</li>


			<li class="splide__slide">
				<img src="2.jpg">
				<div>
					Description 02
				</div>
			</li>
		</ul>
  </div>
</div>



</body>

{{% cta cta_link="./people/" cta_text="团队成员" %}}