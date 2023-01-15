---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: blank

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 20

title: '研究设备'
subtitle: ''


design:
  columns: '1'
  view: compact
---

<html>
<head>
<style>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
div{margin:24px;border:10;padding:10;};
.container1{
background-image:url('fnirs.jpg');
background-repeat:no-repeat;
background-position:left top;
margin-right:200px;

}
    .photo{
        float:left;
        width:100px;
        height:100px;
    }
    .intro{
        float:right;
        width:70%;
    }


</style>
</head>
<body>


<div class="card mb-3" style="max-width: 540px;">
  <div class="row no-gutters">
    <div class="col-md-4">
      <img src="fnirs.jpg" alt="功能性近红外">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">功能性近红外脑成像系统</h5>
        <p class="card-text">fNIRS（功能性近红外光谱）是一种非侵入性神经成像技术，通过记录含氧/脱氧血液量的变化来测量大脑反应。 它基于光散射原理工作——该设备向头皮发射高强度近红外光束，并检测大脑吸收的光量变化。 然后应用数学算法来处理收集到的数据，以计算含氧/脱氧血红蛋白浓度的变化。这些变化与大脑功能的变化有关。</p>
      </div>
    </div>
  </div>
</div>




</body>
</html>