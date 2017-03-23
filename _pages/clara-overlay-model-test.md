---
ID: 119546
post_title: CLARA-OVERLAY-MODEL-TEST
author: Eric Zanke
post_date: 2017-03-23 19:18:03
post_excerpt: ""
layout: page
permalink: >
  http://newlearning.steelcase.com/product/clara-overlay-model-test/
published: true
eg_sources_html5_mp4:
  - ""
eg_sources_html5_ogv:
  - ""
eg_sources_html5_webm:
  - ""
eg_sources_youtube:
  - ""
eg_sources_vimeo:
  - ""
eg_sources_wistia:
  - ""
eg_sources_image:
  - ""
eg_sources_iframe:
  - ""
eg_sources_soundcloud:
  - ""
eg_vimeo_ratio:
  - "0"
eg_youtube_ratio:
  - "0"
eg_wistia_ratio:
  - "0"
eg_html5_ratio:
  - "0"
eg_soundcloud_ratio:
  - "0"
eg_settings_custom_meta_skin:
  - ""
eg_settings_custom_meta_element:
  - ""
eg_settings_custom_meta_setting:
  - ""
eg_settings_custom_meta_style:
  - ""
eg-my-custom-url:
  - ""
eg-lightbox-iframe:
  - ""
---
<code>
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>CLARA-OVERLAY-MODEL</title>


  <!-- CSS -->

  <style type="text/css">
  	
  	#unique {
		visibility: hidden; 
		}

  </style>
  

 
 
</head>

<body>
  <div id="content">
  <div id="clara-embed" style="width: 600px; height: 400px;"></div>
</div>

<div id="unique">
  <p id="text"></p>
</div>

<script src="https://steelcase.clara.io/js/claraplayer.min.js"></script>


 <!-- JS -->
  <script>
const content = {
  'Designed for Wellbeing': 
    'something about Designed for Wellbeing',
  'Workplace Wellbeing': 
    'something about Workplace Wellbeing',
  'Encouraging Health Postures': 
    'something about Encouraging Health Postures',
  'Antimicrobial': 
    'something about Antimicrobial',
  'Collaboration Button': 
    'something about Collaboration Button',
  'Variety of Cable Management Options': 
    'something about Variety of Cable Management Options',
  'Obstruction Sensing': 
    'something about Obstruction Sensing',
  'Health Conscious Environment': 
    'something about Health Conscious Environment',
};

const textDiv = document.getElementById('unique');
const textEl = document.getElementById('text');


var clara = claraplayer('clara-embed'); 
clara.on('loaded', function() { console.log('Clara player is loaded and ready'); }); 
clara.sceneIO.fetchAndUse("1613b124-6f9f-48ca-a2c5-52e40db046aa"); 
clara.on('loaded', () => { 
  const cameras = clara.scene.getAll({type: 'Camera', property: 'name'}); 
  for(let id in cameras) { 
    console.log(cameras[id]);
    let button = document.createElement('button'); 
    button.innerText = cameras[id]; 
    button.onclick = (ev) => { 
      clara.player.animateCameraTo(id, 500); 
      showTextForCamera(cameras[id]);
    }
    document.getElementById('content').appendChild(button); 
  } 
});

function showTextForCamera(name) {
  textDiv.style.visibility = 'visible';
  textEl.innerText = content[name] || '';
}
</script>

</body>
</html>
</code>